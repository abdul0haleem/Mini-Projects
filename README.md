# Mini-Projects

A collection of beginner-friendly Python mini projects built and documented step by step on Kali Linux (VirtualBox). Each project has its own folder with a detailed README, code walkthrough, and screenshots.

## Projects

| # | Project | Description | Tech |
|---|---------|-------------|------|
| 1 | [Caesar Cipher Encryption and Decryption](./caesar-cipher-encryption-and-decryption) | A command-line program that encrypts and decrypts text using a user-defined shift value. Includes a menu, input validation, a continuous loop, and an exit option. | Python 3 |
| 2 | [Pixel Manipulation for Image Encryption](./pixel-manipulation) | Encrypts and decrypts images by adding or subtracting a key from each pixel's RGB values, showing how image data can be processed at the pixel level. | Python 3, Pillow |
| 3 | [Password Complexity Checker](./password-complexity-checker) | Evaluates a password against length, uppercase, lowercase, number, and special-character rules. It gives a score out of 5, classifies the password as Weak, Moderate, or Strong, and suggests improvements. | Python 3 |
| 4 | [Network Packet Analyzer](./network-packet-analyzer-scapy) | Captures live network traffic and analyzes packets, showing protocols, IP addresses, ports, payload data, packet numbers, and timestamps. Also logs packets to a file and includes an interactive menu. | Python 3, Scapy |

## Project Summaries

### 🔐 Caesar Cipher Encryption and Decryption
Takes a message and a shift value, shifts each letter forward to encrypt, and reverses the shift to decrypt. A good introduction to basic cryptography concepts.

### 🖼️ Pixel Manipulation for Image Encryption
Uses Pillow to read an image, modify each pixel's RGB values with a key, and save the encrypted result. Decryption reverses the operation to restore the original image.

### 🛡️ Password Complexity Checker
A password-strength tool that checks five security criteria, calculates a score, and gives specific feedback on what's missing. Demonstrates string handling and conditional logic in a cybersecurity context.

### 📡 Network Packet Analyzer
Built with Scapy, this tool sniffs network packets and progressively adds protocol identification, TCP/UDP analysis, payload inspection, timestamps, and log-file output.

## Environment

- **OS:** Kali Linux
- **Virtualization:** VirtualBox
- **Language:** Python 3
- **Editor:** Nano
