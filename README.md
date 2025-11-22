# Blowfish Cipher (ECB & CBC Modes)

This project provides a Python implementation of the Blowfish block cipher, supporting both ECB (Electronic Codebook) and CBC (Cipher Block Chaining) modes.
It includes key scheduling, S-box loading, block encryption/decryption, and mode operations.

# Features

Complete Blowfish encryption and decryption pipeline

Manual implementation of:
  - P-array initialization
  - S-box loading from external files (sbox1.txt, sbox2.txt, sbox3.txt, sbox4.txt)
  - f-function
  - 16-round Feistel network
  - Key expansion algorithm

Support for:
  - ECB encryption/decryption
  - CBC encryption/decryption with random 64-bit IV

Works on 64-bit blocks (as defined by Blowfish)

Command-line style input for plaintext and mode selection
