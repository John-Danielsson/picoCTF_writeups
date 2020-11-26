## Glory of the Garden
### Category
Forensics
### Problem
The [numbers](./img/the_numbers.png)... what do they mean?
### Hints
1) The flag is in the format PICOCTF{}
### Solution

**STEP 1**

Let's look at the image:

![16 9 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 }](./img/the_numbers.png "What do they mean?")


**STEP 2**

There are 2 curly braces (a left one and a right one), but everything else is a 1 or 2 digit number. That most likely means that it's a substitution cipher (more specifically, the A1Z26 cipher, given that this problem is only worth 50 points), where each letter is substituted with its corresponding place in the alphabet. (a = 1, b = 2, ... , z = 26)

**STEP 3**

Using such a substitution cipher, we can decipher the numbers, which gives us PICOCTF{THENUMBERSMASON}.

Thus, we have the flag:

```PICOCTF{THENUMBERSMASON}```