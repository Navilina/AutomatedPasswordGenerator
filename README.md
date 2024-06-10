# AutomatedPasswordGenerator

Hello there! This script generates a random password based on specified numbers of letters, symbols, and numbers. It then shuffles these characters to ensure a high level of randomness.

How It Works
Initialization:

Import the random module to generate random choices.
Define the number of letters (nr_letters), symbols (nr_symbols), and numbers (nr_numbers) for the password.
Define lists of possible characters (letters, symbols, numbers).
Building the Password List:

Create an empty list password_list to store the characters.
Use a for loop to add a specified number of random letters to password_list.
Use another for loop to add random symbols to the list.
Use a third for loop to add random numbers to the list.
Shuffling:

Print the password_list before shuffling to show the initial order.
Shuffle the password_list to mix the characters randomly using random.shuffle().
Final Password:

Print the password_list after shuffling to show the new order.
Convert the list of characters into a single string using "".join(password_list).
Print the final password.

![image](https://github.com/Navilina/AutomatedPasswordGenerator/assets/136193317/faef07b8-ab62-44c7-86d2-12f7b094a95e)

Feel free to adjust the numbers of letters, symbols, and numbers as needed. This script ensures that your password is random and includes a variety of character types for enhanced security.
