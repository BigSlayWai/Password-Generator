# Password Generator
## Overview
This project is a Python-based password generator that allows users to create strong, customized passwords by specifying the number of letters, symbols, and numbers they want in the password.

### Easy Mode: 
- The generated password maintains a sequence where letters, symbols, and numbers appear in the order specified by the user.
### Hard Mode:
- The generated password has a random order of letters, symbols, and numbers, making it even more secure.

## How It Works
When you run the program, it will prompt you with the following questions:

1. How many letters would you like in your password?
2. How many symbols would you like?
3. How many numbers would you like?
### Example Outputs
#### Easy Mode:
If the user inputs:

- 4 letters
- 2 symbols
- 3 numbers
#### The password might look like this: fgdx$*924

All the letters are grouped together, followed by symbols and then numbers.

#### Hard Mode:
The password is randomized in terms of letter, symbol, and number placement. For the same inputs, the password might look like this: x$d24g*f9

Every time a password is generated, the order of characters will be different, providing enhanced security.
