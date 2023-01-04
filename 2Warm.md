## 2Warm
### Category
General Skills
### Problem
Can you convert the number 42 (base 10) to binary (base 2)?
### Hints
1) Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{11111}' as the flag.
### Solution

**STEP 1**

A good first question to ask is: What numbers that are powers of 2, added up, equal 42? Figure out that answer, and you can easily solve this problem. If you don't know how to write a binary number, look it up.

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
