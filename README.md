# FN-Encrypt

Fn-Encrypt is a desktop application designed to provide robust file encryption and decryption services using AES (Advanced Encryption Standard). The application supports AES-EAX, providing confidentiality and integrity of your files.

## Features

- **File Encryption**: Encrypt files securely using AES-256 bit.
- **File Decryption**: Decrypt files with the provided key and nonce.
- **Key Management**: Automatically handle encryption keys and nonces, with the ability to save them securely.
- **UI Integration**: A user-friendly interface for easy operation.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8 or higher
- PyQt5
- pycryptodome

You can install all required packages using pip:

```bash
pip install PyQt5 pycryptodome

## Installation

git clone this repository
run: Python3 fn.py

## Usage

    Launch the Application: Run the script as mentioned above. The GUI will open.
    Set Encryption Parameters: Choose the encryption mode and key settings.
    Select Files: Use the GUI to select files you wish to encrypt or decrypt.
    Encrypt/Decrypt: Click on the encrypt or decrypt button as required. Progress will be shown on the GUI.
    View Results: Encrypted or decrypted files will be saved in the specified location.

## History

Originally, I started this project as a bank tracker, however, pivoted to a more generalized encryption/decryption app after reading an article that guided me in building my very own app. Attached to this repository is also the original prototype I worked on using the article. 
