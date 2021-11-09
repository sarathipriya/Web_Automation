# Web Automation Project


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This Objective of the project is to test the Web features and functionalities using Copado Testing Tool

# Project Structure
Below is the project structure to be followed for developing Test Suites and Test Cases

**   project_name** (root folder)

├── tests

 	├── ├──my_suite.robot
  
├── resources 

	├── ├──	locators.robot 
	
 	├───├─keywords.robot 

├── libraries 

├──results


## Test Suites and Test Cases
The hierarchical structure for arranging test cases is built as follows:
- A directory containing test case files forms a higher-level test suite.
- Test cases are created in test case files
- resource files holds the locator.robot [ which holds  all xpath used in testing] and keywords.robot [which holds the higher level user keywords]
## KEYWORDS
Below are the keywords used throughout the implementation
- BuiltIn Keyword
- Custom Keywords
- User level Keywords

## Code nomenclature

-   Used business terminology in code. It helps to understanding the problem.
-   Used descriptive names for tasks, keywords, arguments, variables, classes, methods.
- Avoided Sleep throughout the implementation
-   Use comments when they provide value and when the code cannot communicate the "why"
- CODE REUSABALITY:- Implemented User level keyword to avoid repeat same steps again
