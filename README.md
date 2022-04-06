# AS-JsonParserSample
Project containing program to obtain data from .json files in a defined structure, written in ST

## 1. Project Description
This project was created to obtain data from .json files inside a defined structure.
Two test files are located in the Logical View (init.json and fin.json).
Their structure is defined in the action ConfigJson.st.
The file is deleted after reading.

To retrieve and copy the data from the file, the library STANDARD and AsBrStr are used.
The files are accessed through FileDevices and using the library FileIO.
This project was created using AS V4.7.7.74


## 2. How to install and run the project
This project can be opened using AS  V4.7.7.74.


## 3. How to use the project
There's a task inside the project called JsonParser.
The variable gJsonParser.Cmd.Start must be set to true to start the state machine.


## 4. How to contribute / To do's
Suggestions are welcome.
Maybe a version in .c will be developed, in order to dynamic memory allocation.
