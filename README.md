# AESCrypto-V11

AESCrypto-V11 is a secure text encryption tool designed to provide strong, password-based encryption using Advanced Encryption Standard (AES) with enhanced security features. This project is based on the original [AES Crypto](https://aescrypto.com) by Evgenii Neumerzhitski, with improvements in key derivation and password security. 

**Features:**
- **PBKDF2 Key Derivation:** Utilizes PBKDF2 with SHA-256 hashing and 10,000 iterations for secure key derivation, making it resistant to brute-force attacks.
- **AES-256 Encryption:** Encrypts messages with AES-256 in CBC mode for high-level security.
- **Random Salt Generation:** Each encryption uses a random salt and initialization vector (IV) for additional security, even if the same password is used multiple times.
- **Simple Interface:** Easy-to-use HTML interface for encrypting and decrypting messages securely.
- **Open Source:** Released under the MIT license.

## Getting Started

These instructions will help you set up and use AESCrypto-V11 on your local system. 

### Prerequisites

To run AESCrypto-V11, you only need a modern web browser. The app is written in HTML and JavaScript, so no installation or backend server is required.

### Files

1. `index.html` - The main HTML file for AESCrypto-V11.
2. `crypto-js.min.js` - The CryptoJS library for cryptographic functions.
3. `seedrandom.min.js` - Optional for RNG purposes (if not included, CryptoJS's RNG will be used).

> **Note:** For offline use, download the `crypto-js.min.js` file from a trusted source such as [cdnjs](https://cdnjs.com/) and link it locally.

## Usage

1. Open `index.html` in your browser.
2. Enter the **Site Tag** (for identifying the specific purpose, e.g., "example.com").
3. Enter a **Master Key** (your primary password).
4. Specify the **Password Length** (between 14 and 128 characters).
5. Click **Encrypt** to encrypt your message, or **Decrypt** to reveal an encrypted message.

The generated password will appear in the text area below, ready to copy.

### Example

1. **Encrypt:**  
   - Site Tag: `example.com`
   - Master Key: `mysecurepassword`
   - Password Length: `18`

   Click "Encrypt" to generate an encrypted output.

2. **Decrypt:**  
   - Paste the encrypted text in the text box.
   - Enter the **same** Site Tag and Master Key.
   - Click "Decrypt" to reveal the original message.

### Security Notes

- AESCrypto-V11 uses a strong key derivation process with PBKDF2, making it resistant to brute-force and rainbow table attacks.
- Always use a strong Master Key to maximize security.
- Ensure that you do not lose your Master Key, as it is required for decryption.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Attribution:**  
Based on AES Crypto by [Evgenii Neumerzhitski](https://aescrypto.com), with modifications for enhanced security and usability.

## Contributing

Feel free to submit pull requests for bug fixes, feature improvements, or documentation enhancements. Contributions that further improve security and usability are welcome!

## Disclaimer

AESCrypto-V11 is intended for personal use and educational purposes. While it provides a strong level of encryption, no security software is foolproof. Use this software responsibly and ensure backups of any encrypted data.
