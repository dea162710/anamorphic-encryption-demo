# Anamorphic Encryption: Private Communication against a Dictator

## Contents
- `presentation.pdf`: 8-slide summary of the base paper.
- `anamorphic_encryption.py`: Conceptual Python demo of anamorphic encryption.
- ' # Anamorphic Encryption Demo (Educational Implementation)

This project is a simplified implementation and demonstration of key concepts from the paper:

**"Anamorphic Encryption: Private Communication Against a Dictator"**  
[https://eprint.iacr.org/2022/639.pdf](https://eprint.iacr.org/2022/639.pdf)

It was created as part of a high school internship project to help understand modern cryptography research. This code **simulates** the paper’s constructions in a beginner-friendly way using Python.

> ⚠️ **Disclaimer:** This might not be a complete version but it is the best I could do. I did have to look up some things from videos but nothing from AI. 

---

## 🔍 The things that I put in the DEMO 

This demo shows simplified versions of the constructions in Sections 4, 5, and 6 of the paper:

### 1. Section 4 – Receiver-Anamorphic Encryption
- Simulates a user sending a normal message for the dictator
- Hides a secret message inside it
- Uses real RSA keys and encryption from pycryptodome

### 2. Section 5 – Rejection Sampling & Naor-Yung Transform
- Rejection Sampling: Uses a simulated PRF to encode a hidden bit into a ciphertext string
- Naor-Yung : Demonstrates dual encryption + fake zero-knowledge proof (placeholder)

### 3. Section 6 – Sender-Anamorphic Encryption (Simulated)
- Shows a sender creating a ciphertext that looks normal to one recipient but secretly decodes to a different message for another
- Randomly tries ciphertexts until one "fits"

---
