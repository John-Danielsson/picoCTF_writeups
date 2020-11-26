## caesar
### Category
Cryptography
### Problem
Decrypt this [message](./misc_files/ciphertext).
### Hints
1) caesar cipher [tutorial](https://learncryptography.com/classical-encryption/caesar-cipher)
### Solution

**STEP 1**

It looks like the flag is already given to us with ```picoCTF{dspttjohuifsvcjdpoabrkttds}```, but the content within the braces is enciphered with a caesar cipher as implied by the hint.

*Here's a [link](https://cryptii.com) to a great caesar cipher decoder.*

**STEP 2**

Running the ciphertext inside the curly braces through a caesar cipher decoder, we find that the plaintext is "crossingtherubiconzaqjsscr".

Thus, we have the flag:

```picoCTF{crossingtherubiconzaqjsscr}```
