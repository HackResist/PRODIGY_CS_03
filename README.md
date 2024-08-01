# Password Complexity Checker
> If you like this repository, don't forget to give it a ⭐!
## Overview
The Password Complexity Checker is a Python-based graphical user interface (GUI) application built using Tkinter. This tool allows users to evaluate the strength of their passwords, generate random secure passwords, and copy them to the clipboard. The application provides immediate feedback on password strength and offers a visually engaging experience with hover effects and progress animations.

## Features

  - **Password Strength Evaluation:** Analyze your password and get a strength score based on the presence of lowercase letters, uppercase letters, digits, spaces, and special characters.
  - **Password Generation:** Generate a secure random password containing letters, digits, and special characters.
  - **Clipboard Copying:** Easily copy the generated or entered password to the clipboard with a confirmation dialog.
  - **Password Visibility Toggle:** Toggle between showing and hiding the entered password.
  - **Clear Input:** Clear the current password entry with a single click.

## Installation

  1. Clone this repository or download this repository.
  2. Install required libraries just using this command `pip install pyperclip`.
## Dependencies
  - **Python 3.x**
  - **Tkinter:** Comes pre-installed with Python.
  - **pyperclip:** For copying text to the clipboard.

## User Interface
  - **Input Field:** A text entry box for typing or pasting your password.
  - **Buttons:**
      - **Check:** Evaluates the entered password.
      - **Generate Password:** Creates a new random password.
      - **Copy Password:** Copies the password to the clipboard.
      - **Clear:** Clears the password input.
      - **👀 Show / 🙈 Hide:** Toggles password visibility.
  - **Output Area:** Displays the results of the password evaluation, including the password score and feedback.
  - **Progress Meter:** A visual representation of password strength, with colors ranging from red (weak) to green (strong).
