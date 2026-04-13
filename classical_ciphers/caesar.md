# Caesar Cipher

## Overview
The Caesar cipher is a substitution cipher where each letter is shifted by a fixed number of positions in the alphabet.

## Decryption Formula
P = (C - k) mod 26

## Example

Ciphertext:
WKH

Manual Decryption:
W (22 - 3) = T  
K (10 - 3) = H  
H (7 - 3) = E  

Plaintext:
THE

## Security Insight
The Caesar cipher is weak because:
- Only 25 possible keys exist
- Easily broken using brute force
- Frequency analysis can quickly reveal the key
