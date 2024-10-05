## OASIS INFOBYTE TASK 2

# RANDOM PASSWORD GENERATOR

## Overview of the project

For my 2nd task in my internship in Python Programming at Oasis Infobyte, I chose to develop a random password generator.

## Objectives of the project  

- Create a command-line random password generator
- It should generate random passwords based on user-defined criteria
- These criteria include length of the password and character set preferences, which should be taken as user inputs

## Implementation of the project  

The implementation of the project was done through the following steps : 
- First, I imported the modules random and string which would be required for this project.
- I took both minimum password length and maximum password length as inputs from the user.
- For the character sets of numbers, letters and symbols, the user would have to enter 1 to include the specific set and 0 to discard it, based on which the character set for the password was defined.
- The length of the password was chosen as an intermediate value between its minimum and maximum limits using the random.choice() function.
- I used a for loop to iterate over the indices of the password and for each index, a specific character was chosen from the character set of the password.
- The randomly chosen character was concatenated to the password string to generate the random password.

![Screenshot (94)](https://github.com/user-attachments/assets/7504fdbc-e7ed-49fd-b7dc-67633ee3e1e2)
