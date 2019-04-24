# Timetable Scheduling Program

## Setup

To start a new project, you will have to prepare the following files and get ready to upload:

- lecture info workbook (Excel);

- course selection workbook (Excel);

- and a directory where all timetable scheduling results will be saved.

You can get the templates of two workbooks (mentioned above) in the <resources> folder under this repository. Please start formating your data using templates provided.

## User Manual

- Click the <Clone or download> button (which is located at the top-right corner of this page) to download the whole project to a zipped file
 
- Uncompress the zip and run timetable.jar

- Click the <Start New Project> button and follow the instructions


## Functional Requirements

This system only works for current G11 students of Shanghai Qibao Dwight High School. Support for G10 and G12 students will be released soon. 

The program is able to output at most four types of results:

- timetable.csv (default) 

- course-summary.csv (default)

- student-list-for-each-course.csv (default)

- timetable-for-each-student.pdf (optional)

Please note that this program, like all optimization programs, cannot ensure a good result will be returned in polynomial time, i.e., there is little possibility that the program will run to a dead end and never stop. Hence, in this case, please restart the software and run again. I tested the reliablity of this program and found it is about 95% reliable (1 out of 20 never stops).
