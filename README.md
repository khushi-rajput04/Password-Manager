# Password-Manager

This is a simple password manager application created using Python's Tkinter library. It allows users to generate strong passwords and store them along with website and email details.

## Functionalities

### Password Generation
- Clicking the "Generate Password" button creates a random strong password consisting of letters (both uppercase and lowercase), numbers, and symbols.
- The generated password is automatically copied to the clipboard for easy use.

### Saving Passwords
- Users can enter the website, email, and password details into the respective fields.
- The user is prompted if any field is left empty.
- Clicking the "Add" button stores the entered details in a text file named `data.txt` in the same directory as the script.
- Before saving, the user is prompted to confirm the details entered. If confirmed, the details are saved; otherwise, the operation is canceled.

## How to Use
1. Run the Python script `main.py`.
2. Enter the website, email, and password details into the respective fields.
3. Click the "Generate Password" button to create a random strong password, or manually enter a password.
4. Click the "Add" button to save the entered details.
5. Confirm the details entered when prompted.
6. The details are saved in the `data.txt` file for future reference.

## Requirements
- Python 3.x
- Tkinter library

![Password Manager Logo](https://github.com/khushi-rajput04/Password-Manager/blob/main/app.png)
