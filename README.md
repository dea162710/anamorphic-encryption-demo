# Anamorphic Encryption: Private Communication against a Dictator

## Contents
- `presentation.pdf`: 8-slide summary of the base paper.
- `anamorphic_encryption.py`: Conceptual Python demo of anamorphic encryption.
- ' # Anamorphic Encryption Demo (Educational Implementation)

This project is a simplified implementation and demonstration of key concepts from the paper:

**"Anamorphic Encryption: Private Communication Against a Dictator"**  
[https://eprint.iacr.org/2022/639.pdf](https://eprint.iacr.org/2022/639.pdf)

This code **simulates** the paper’s constructions in a beginner-friendly way using Python.

> ⚠️ **Disclaimer:** This might not be a complete version but it is the best I could do. I did have to look up some things from videos but nothing from AI. Here are the links that I used besides the main paper: https://pycryptodome.readthedocs.io/en/latest/src/public_key/rsa.html, https://pycryptodome.readthedocs.io/en/latest/src/examples.html#encrypt-data-with-rsa, https://docs.python.org/3/library/base64.html, https://docs.python.org/3/library/hashlib.html, https://crypto.stanford.edu/~dabo/courses/cs255_winter12/, https://www.youtube.com/watch?v=wXB-V_Keiu8

---

## 🔍 The things that I put in the DEMO 

This demo shows simplified versions of the constructions in Sections 4, 5, and 6 of the paper:

### 1. Section 4 – Receiver-Anamorphic Encryption
- Shows that  a user sending a normal message for the dictator to read 
- However, it is going to hide  a secret message inside it
- Uses real RSA keys and encryption from pycryptodome

### 2. Section 5 – Rejection Sampling & Naor-Yung Transform
- Rejection Sampling: Uses a simulated PRF to encode a hidden bit into a ciphertext string
- Naor-Yung : Demonstrates dual encryption + fake zero-knowledge proof (placeholder)

### 3. Section 6 – Sender-Anamorphic Encryption (Simulated)
- Shows a ciphertext that looks normal, but then gives a different one 
- Randomly tries ciphertexts until one "fits"

---
