# ADVANCED-ENCRYPTION-TOOL
*COMAPANY* : CODTECH IT SOLUTIONS

*NAME* : ANUBHAV KUMAR

*INTERN ID* : CT04DF1662

*DOMAIN* : Cyber Security & Ethical Hacking

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH
# DESCRIPTION
This File Encryption and Decryption Tool is a secure Python-based utility that uses the AES-256 (Advanced Encryption Standard) algorithm in CBC mode to protect sensitive files. It employs a password-based key derivation function (PBKDF2 with SHA-256 and salt) to generate strong encryption keys, ensuring confidentiality. The tool supports encryption and decryption of any file type, applying proper padding and securely storing metadata like the salt and IV. Designed for simplicity and security, it enables users to protect personal or confidential data from unauthorized access through a command-line interface. This tool is ideal for cybersecurity enthusiasts, professionals, and secure file sharing.

# TOOLS AND LIBRARIES USED:
Python Standard Libraries

Library   -    	Purpose

os    -       	Generate random bytes for salt and IV, handle file paths

getpass   - 	  Securely input passwords (hides password in terminal)

argparse    - 	Command-line argument parsing

base64    -     (optional)	Encode/decode keys (not used in file I/O, but useful for readable output)

Third-Party Library

Component         - 	Purpose

PBKDF2HMAC       -  	Derives a strong key from a password using salt and SHA-256

AES             -   	The AES encryption algorithm used in 256-bit mode

CBC             -   	Cipher Block Chaining mode for AES (adds randomness with IV)

Cipher          -    	High-level interface to encrypt/decrypt data securely

default_backend -    	Backend provider used by the cryptography library for cryptographic operations

hashes.SHA256   -    	Secure hashing algorithm used in key derivation

# KEY FEATURES:
Feature      -  	          Description

🔐 AES-256 Encryption   -  	Uses 256-bit Advanced Encryption Standard for strong file protection.

🧂 Salted Key Derivation -  	Implements PBKDF2 with SHA-256 and random salt to securely derive encryption keys from passwords.

🔁 CBC Mode with IV     -   	Uses Cipher Block Chaining (CBC) mode and a random Initialization Vector (IV) for enhanced security.

📂 File-Type Agnostic   -   	Works with all file types: text, images, documents, binaries, etc.

👤 Password-Based Protection - 	Users provide a password—no need to manage or store encryption keys manually.

🔒 Secure Padding   -        	Uses PKCS#7 padding to ensure data blocks align properly with AES block size.

📁 Clean Output    -       	Produces .enc files for encrypted data and .dec files for decrypted output.

🖥️ Command-Line Interface (CLI)	   -  Simple and intuitive CLI for both encryption and decryption operations.

⚙️ Stateless Operation      - 	No user data or keys are stored—ensures privacy and portability.

📜 Cross-Platform Support    - 	Works on Windows, Linux, and macOS systems with Python installed.
# USE CASES
Use Case	           -    Description

🔐 Secure File Storage	   -  Encrypt sensitive documents (e.g., contracts, reports, IDs) to prevent unauthorized access on local or cloud storage.

📤 Safe File Sharing       -	Send encrypted files via email or external drives, ensuring only the intended recipient with the password can decrypt them.

🛡️ Data Protection for Professionals  -  	Useful for lawyers, journalists, auditors, and researchers handling confidential information.

🧪 Cybersecurity Training	       -  Ideal for teaching encryption basics and secure key derivation in educational labs or workshops.

🧳 Travel Security       -     	Protect personal files while traveling, in case of device loss or theft.

🗄️ Secure Backups	      -      Encrypt backups before uploading to cloud services like Google Drive or Dropbox.

👨‍💻 Developer Tooling         -	Use as part of a secure DevOps pipeline to protect environment files or configuration data.

🕵️‍♂️ Personal Privacy     -    	Encrypt diary entries, financial records, or personal photos stored on disk.
