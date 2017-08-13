# Course Manager

How to compile the code

1. Download the source files and place them in a folder called "course_mgr"
2. Open up terminal and navigate inside "course_mgr" directory
3. Use g++ to compile the c++ code. Use the following command: `g++ -std=c++11 -o course_mgr *.cpp`
4. Execute `./course_mgr` in terminal to launch the app.

Bugs to investigate
* Changing study load of a course adds to the current course load instead of overriding the old value
* Selecting change study load of a course option and typing in gibberish will cause menu to skip user input once.
It returns "invalid input" error instead.

## Screenshots
![alt text](screenshots/1.png "main menu")
![alt text](screenshots/2.png "adding a course")
![alt text](screenshots/3.png "listing courses")
![alt text](screenshots/8.png "saving and reloading data")
