## vault-door-training
### Category
General Skills
### Problem
What is 0x3D (base 16) in decimal (base 10)?
### Hints
1) Submit your answer in our flag format. For example, if your answer was '22', you would submit 'picoCTF{22}' as the flag.
### Solution

**STEP 1**

Since this is base 16, we don't need to worry about the ```0x``` part in ```0x3D``` _[1]_. But we do need to look at the ```3D``` part.

**STEP 2**

Since we are dealing with base 16 here, we can break ```3D``` down into ```3*16 + 13``` _[2]_, which equals ```61```.

Thus, we have the flag:

```picoCTF{61}```

_[1]_ ```0x``` is a prefix indicating that 0x3D is a base 16 number. Base 16 is also called "hexadecimal" or "hex".

_[2]_ Since there are only 10 base 10 digits, we use letters to represent the other 6 digits in base 16. The order of digits goes like this: 0 1 2 3 4 5 6 7 8 9 A B C D E F