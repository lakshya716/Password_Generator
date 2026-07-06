# Password Generator

A simple command-line password generator built using Python. It allows users to generate random passwords based on their preferred length and character types.

## Features

* Choose the password length
* Include uppercase letters
* Include lowercase letters
* Include numbers
* Include special characters
* Generates a random password based on selected options
* Handles cases where no character type is selected

## Technologies Used

* Python
* `random` module
* `string` module

## How It Works

The program asks the user to:

1. Enter the desired password length
2. Choose whether to include uppercase letters
3. Choose whether to include lowercase letters
4. Choose whether to include numbers
5. Choose whether to include special characters

Based on the selected options, the program creates a pool of characters and randomly selects characters from it to generate the password.

## Example

```text
Password Generator

Enter password length: 12

Choose what you want in your password:
Include uppercase letters? (y/n): y
Include lowercase letters? (y/n): y
Include numbers? (y/n): y
Include special characters? (y/n): y

Generated password: K7@pL2#xQ9!m
```

## How to Run

1. Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder:

```bash
cd password-generator
```

3. Run the Python file:

```bash
python password_generator.py
```

## Requirements

* Python 3.x

No external libraries are required.

## Project Structure

```text
password-generator/
│
├── main.py
└── README.md
```

## Future Improvements

* Add password strength checking
* Allow users to generate multiple passwords at once
* Add better input validation
* Build a graphical user interface using Tkinter

## Author

Lakshya
