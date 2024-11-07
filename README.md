# Password Strength Assessment Tool

This is a simple Python tool that assesses the strength of a password based on specific criteria. It provides feedback on how to improve password strength, making it a useful tool for users who want to ensure they have secure passwords.

## Features

- **Password Length Check**: Ensures the password is at least 8 characters long.
- **Uppercase and Lowercase Check**: Verifies the password contains both uppercase and lowercase letters.
- **Number Check**: Confirms that the password includes at least one numeric character.
- **Special Character Check**: Checks for at least one special character from a set of commonly used symbols.

Based on these criteria, the tool rates the password as "weak," "medium strength," or "strong" and provides feedback to help improve it.

## How It Works

The program uses regular expressions to identify the presence of required elements in the password. It assigns a score and generates feedback messages to let the user know which elements are missing.

## Prerequisites

- **Python 3.x**: Ensure you have Python 3 installed on your system.

## Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/shahsad1234/PRODIGY_03
    cd password-strength-assessment-tool
    ```

2. **Run the program**:
    ```bash
    python password_strength_tool.py
    ```

## Usage

1. Run the program by executing `password_strength_tool.py`.
2. Enter your password when prompted.
3. The program will assess the password strength and provide feedback on how to improve it.

### Example Output

**Weak Password**:


**Strong Password**:

## Project Structure


## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Python Regular Expressions (re)](https://docs.python.org/3/library/re.html) - Used for pattern matching
