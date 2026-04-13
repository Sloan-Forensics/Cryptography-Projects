# AES and Block Cipher Modes

## ECB Mode
- Identical plaintext blocks → identical ciphertext
- Patterns remain visible
- Not secure

## CBC Mode
- Each block depends on previous ciphertext
- Uses Initialization Vector (IV)
- Produces more random output

## Avalanche Effect
A small change in input results in a large change in output.

## Security Insight
Modern encryption relies on:
- Confusion (complex transformations)
- Diffusion (spreading changes across data)
