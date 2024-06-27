Encryption Ciphers
This repository contains implementations of three encryption ciphers: Caesar Cipher, Monoalphabetic Cipher, and Playfair Cipher. Each cipher provides both encryption and decryption functionalities.

Caesar Cipher
The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

Functions:
caesar_cipher_encrypt(plaintext, key): Encrypts the given plaintext using the provided key.
caesar_cipher_decrypt(ciphertext, key): Decrypts the given ciphertext using the provided key.

Monoalphabetic Cipher
The Monoalphabetic Cipher is a substitution cipher where each letter in the plaintext is mapped to a fixed letter in the alphabet.

Functions:
monoalphabetic_encrypt(plaintext, key): Encrypts the given plaintext using the provided key.

Playfair Cipher
The Playfair Cipher is a digraph substitution cipher where pairs of letters are encrypted together based on a 5x5 matrix generated from a keyword.

Functions:
generate_playfair_matrix(key): Generates a 5x5 matrix based on the provided key.
playfair_encrypt(plain_text, matrix): Encrypts the given plain text using the provided matrix.
playfair_decrypt(encrypted_text, matrix): Decrypts the given encrypted text using the provided matrix.
