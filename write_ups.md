# picoCTF write-ups

## 2Warm
### Problem
Can you convert the number 42 (base 10) to binary (base 2)?
### Hints
Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{11111}' as the flag.
### Solution
This problem is very simple, akin to converting meters to centimeters or vice versa. Here's the breakdown:

**STEP 1**
A good first question to ask is: What number, ```2^n```, where ```n``` is a positive integer and ```2^n <= 42```, but ```2^(n+1)``` is greater than ```42```? That number is ```32``` (equal to ```2^5```), Since ```42 % 2 = 0```, we know that we'll have a ```0``` on the end of this binary number (we won't need to add ```1``` to make the number odd). Below is a breakdown of the binary number:

1 32 32 
0 16 32
1 8  40
0 4  40
1 2  42
0 1  42
32 8 2 

101010
