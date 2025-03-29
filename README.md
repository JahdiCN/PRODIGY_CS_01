# Caesar Cipher Program

## Description
This is a Python implementation of the Caesar Cipher, a simple encryption technique that shifts letters in the alphabet by a specified number of positions. The program allows users to encrypt and decrypt messages interactively.
## Features
- Encrypts a given message using a specified shift value.
- Decrypts an encrypted message by shifting characters back.
- Handles both uppercase and lowercase letters.
- Ignores non-alphabetic characters (they remain unchanged).
- Provides an interactive command-line interface.

## How It Works
- The user inputs a message.
- The user specifies a shift value (positive for encryption, negative for decryption).
- The user chooses to either encrypt or decrypt the message.
- The program outputs the transformed text.
- The user can continue using the program or exit.

## Installation
### Prerequisites
- Python 3.x must be installed on your system.

## Usage
- Run the program in a terminal or command prompt.
- Enter the message you want to encrypt or decrypt.
- Provide a shift value (e.g., 3 for a right shift, -3 for a left shift).
- Choose (e)ncrypt or (d)ecrypt.
- View the transformed message.
- Continue or exit as needed.

## Example
```sh
Welcome to the Caesar Cipher Program!
Enter the message: Hello World!
Enter the shift value (positive for encryption, negative for decryption): 3
Do you want to (e)ncrypt or (d)ecrypt the message? (e/d): e
Encrypted Message: Khoor Zruog!
```
## Notes
- The program correctly handles cases where the shift value is larger than 26 by wrapping around the alphabet.
- Non-alphabetic characters are not modified.

## License
- This project is open-source and available under the MIT License.

## Author
- Your Name (Replace this with your actual name or GitHub username).
