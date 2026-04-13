# RSA Cryptography

## Overview
RSA is an asymmetric encryption algorithm using a public and private key pair.

## Key Concepts
- Public key (e, n)
- Private key (d)
- Encryption and decryption algorithms

## Security Principle
RSA relies on the difficulty of factoring large numbers:
n = p × q

## Vulnerability Insight
If an attacker discovers one factor of n:
- They can compute the other factor
- Derive Euler’s Totient
- Calculate the private key

## Security Insight
RSA is secure only if:
- Prime factors remain secret
- A new modulus is generated if keys are compromised
