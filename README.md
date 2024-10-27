# AESCrypto-V11

AESCrypto-V11 is a secure text encryption tool designed to provide strong, password-based encryption using Advanced Encryption Standard (AES) with enhanced security features. This project is based on the original [AES Crypto](https://aescrypto.com) by Evgenii Neumerzhitski, with improvements in key derivation and password security. 

**Features:**
- **PBKDF2 Key Derivation:** Utilizes PBKDF2 with SHA-256 hashing and 10,000 iterations for secure key derivation, making it resistant to brute-force attacks.
- **AES-256 Encryption:** Encrypts messages with AES-256 in CBC mode for high-level security.
- **Random Salt Generation:** Each encryption uses a random salt and initialization vector (IV) for additional security, even if the same password is used multiple times.
- **Simple Interface:** Easy-to-use HTML interface for encrypting and decrypting messages securely.
- **Open Source:** Released under the MIT license.

### Security Notes

- AESCrypto-V11 uses a strong key derivation process with PBKDF2, making it resistant to brute-force and rainbow table attacks.
- Always use a strong password to maximize security.
- Ensure that you do not lose your password, as it is required for decryption.

**Attribution:**  
Based on AES Crypto by [Evgenii Neumerzhitski](https://aescrypto.com).

## Contributing

Feel free to submit pull requests for bug fixes, feature improvements, or documentation enhancements. Contributions that further improve security and usability are welcome!

## Disclaimer

AESCrypto-V11 is intended for personal use and educational purposes. While it provides a strong level of encryption, no security software is foolproof. Use this software responsibly and ensure backups of any encrypted data.
