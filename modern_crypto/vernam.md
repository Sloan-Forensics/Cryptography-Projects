# Vernam Cipher (One-Time Pad)

## Formula
K = M ⊕ C

## Example
M = HOTEL  
C = NOJTE  

Derived Key:
TALON

## Key Weakness
If the same key is reused:
C1 ⊕ C2 = M1 ⊕ M2

This allows attackers to recover plaintext messages.

## Security Insight
The Vernam cipher is only secure if:
- The key is truly random
- The key is never reused
