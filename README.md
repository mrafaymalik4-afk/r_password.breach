# Simple Password Breach System 🛡️

A lightweight Python script that evaluates **password strength** and checks inputs against a dictionary of **commonly breached passwords**.

## Features
* **Length Validation:** Checks if the password is at least 8 characters long.
* **Character Diversity Checks:** Verifies the presence of numbers, uppercase letters, and special characters.
* **Breach Detection:** Compares the password against a built-in list of leaked or common passwords.
* **Strength Scoring:** Provides an immediate strength score out of 4.

## How It Works
1. The script prompts you to securely enter a password.
2. It evaluates the password across 4 distinct security criteria.
3. It screens the entry against known compromised terms (like `123456789` or `letmein123`).
4. It outputs your final score and safety warning.

## Requirements
* **Python 3.x** (No external libraries required; uses built-in modules).

## Quick Start
1. Clone this repository or copy the code from `main.py`.
2. Run the script using your terminal:
   ```bash
   python main.py
   ```
3. Enter a password when prompted to see your results.

## Future Roadmap
* Integrate with live breach databases via the *Have I Been Pwned* API.
* Add masked password input masking using the `getpass` library.
