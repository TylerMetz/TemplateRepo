# TemplateRepo

## Getting Started
You must first. cd cpputest, then git `submodule init`, then `git submodule update`. Then execute then commands and about 500 tests should pass then you are ready to go.
`autoreconf . -i`
`./configure`
`make tdd`
## Basic Layout
All project files will be in src/code,
src/main.cpp compiles the main project,
t/main.cpp runs all tests,
t/test.cpp holds an example test using code.h,
## Compiling from terminal
The two bash scripts are app and tdd.
To compile just the tests without main runnings you will execute ./tdd,
To compile main without the tests running execute ./app

## Script Permission
If those scripts do not run go into terminal in this directory and do
"chmod +x scriptname.sh"


## Proper Naming
Currently the output executable is called "example." Hopefully you change this, I have marked everywhere you should change it with "change here."
Hit "CMD+Shift+F" and enter change here to find all the instances and change them to what you would like the new executable to be called