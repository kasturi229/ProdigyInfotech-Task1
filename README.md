# ProdigyInfotech-Task1
The Caesar cipher is a simple encryption technique where each letter in the plaintext is shifted by a fixed number of positions down or up the alphabet. It’s named after Julius Caesar,.While it’s easy to implement, it’s also very vulnerable to attacks, especially with modern computing power.
The Caesar cipher is a substitution cipher, one of the earliest and simplest forms of encryption. It works by shifting each letter of the plaintext by a fixed number of positions in the alphabet.

How it Works:
Shift: Each letter of the plaintext is shifted by a certain number of positions down or up the alphabet. The number of positions to shift is called the shift value or key.

Example:

With a shift of 3, the letter "A" becomes "D", "B" becomes "E", "C" becomes "F", and so on.

The alphabet wraps around; for example, "Z" shifted by 1 becomes "A".

Encryption:

Given a letter, its position in the alphabet (0 for A, 1 for B, etc.) is found, and the shift is applied.

For a shift of 3, the position of each letter is increased by 3, and then it wraps around if necessary (i.e., "Z" becomes "C").

Formula:

Encrypted letter
=
(Position of letter + Shift) mod 26

Encrypted letter=(Position of letter+Shift)mod26

This formula ensures that when a letter is shifted past 'Z', it wraps around to the beginning of the alphabet.

Decryption:

To reverse the process, decryption is done by shifting the letters backward by the same number of positions.

Decryption formula:

Decrypted letter
=
( Position of letter − Shift ) mod 26

Decrypted letter=(Position of letter−Shift)mod26

This shifts letters back to their original positions.
