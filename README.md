# python-password-projects
in this project, I've worked on two different programs.
Password-generator and Password-estimator

1. Password Generator:
in this program, I've used two modules namely {"random"} and {"zxcvbn" by dropbox - password strength estimater}

2. Password Strength estimator:
though the program name and the module description is same, in this program, there are no changes made except, the user will input the password of their choice within the given length and checks if the password is met upto the certain criteria.

Aim:
to generate or input password with 10 characters aligning with:
    1. both upper and lower case letters (A-Z, a-z)
    2. numbers (0-9)
    3. Special symbols (!@#$%^&*)

Algorithm:
-   Creating a list of uppercase & lowercase letters, digits and special characters
-   merging all the characters into one master list
-   using python's "random" module, select the characters from the combined list (master list)
-   ensure atleast one character from each category is present for stronger security
-   shuffle and join the characters into a final password string
-   display and return the password to the user
(Updated)
- display the generated password strength 
- if the strength score is less than or equal to 2,
    - display a warning + suggestions from 'zxcvbn'
    - auto-generate 3 stronger password alternatives
    else
    - accept as stronger

improvement: 
^ importing 'zxcvbn' - an intelligent password strength estimator, developed by DropBox
^ show a warning and suggest 3 stronger alternative passwords
