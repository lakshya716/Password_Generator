import random
import string

print("Password Generator")

length = int(input("Enter password length: "))

print("\nChoose what you want in your password:")
upper = input("Include uppercase letters? (y/n): ").lower()
lower = input("Include lowercase letters? (y/n): ").lower()
numbers = input("Include numbers? (y/n): ").lower()
symbols = input("Include special characters? (y/n): ").lower()

characters = ""

if upper == "y":
    characters += string.ascii_uppercase

if lower == "y":
    characters += string.ascii_lowercase

if numbers == "y":
    characters += string.digits

if symbols == "y":
    characters += string.punctuation

if characters == "":
    print("Please select at least one character type.")

elif length <= 0:
    print("Password length should be greater than 0.")

else:
    password = ""

    for i in range(length):
        password += random.choice(characters)

    print("\nGenerated password:", password)
