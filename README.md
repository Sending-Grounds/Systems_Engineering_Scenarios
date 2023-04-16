# Systems_Engineering_Scenarios
This is a serious of scenarios for KillerCoda platform to help teach Systems Engineering from soup to nuts:

This will contain courses on:
* Certs (such as LFCS and RHCSA)
* Systems Engineering basics (Troubleshooting an application, configuring a web server, writing automation, etc...)

## Structure
This repo/package is structured in the following way: 
* KillerCoda has a `structure.json` file, and once available only the information from that file will be used for setting up the scenarios
* Any directory we create outside of that `structure.json` will be ignored.
* Scenarios in a subdirectory (that is listed in the `structure.json` file) are considered a group or course.
* In order to have more complexy structures, like multiple courses and scenarios within a course, you must use the `structure.json` file