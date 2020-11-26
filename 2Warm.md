## 2Warm
### Category
General Skills
### Problem
Can you convert the number 42 (base 10) to binary (base 2)?
### Hints
1) Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{11111}' as the flag.
### Solution

**STEP 1**

A good first question to ask is: What number, ```2^n```, where ```n``` is a positive integer, is less than or equal to ```42```, but ```2^(n+1)``` is greater than ```42```?

That number is ```32``` (equal to ```2^5```).

**STEP 2**

Since ```42 % 2 = 0```, we know that we'll have a ```0``` on the end of this binary number (we won't need to add ```1``` to make the number odd). Below is a table breakdown of the binary number:

Binary Digit | Value | Sum
--------------------------
1  | 32 | 32 
0  | 16 | 32
1  | 8  | 40
0  | 4  | 40
1  | 2  | 42
0  | 1  | 42

Thus, we have 101010 as our answer. Below is the flag:

```picoCTF{101010}```