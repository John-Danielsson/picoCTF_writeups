## Bases
### Category
General Skills
### Problem
What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases.
### Hints
1) Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.
### Solution

**STEP 1**

The problem statement suggests that bDNhcm5fdGgzX3IwcDM1 might be encoded in a base of some sort.

**STEP 2**

The sequence bDNhcm5fdGgzX3IwcDM1 is encoded in base 64. If we run it through a base 64 decoder, we get the string "l3arn_th3_r0p35". 

([Base 64 Wikipedia page](https://en.wikipedia.org/wiki/Base64))

Thus, we have the flag:

```picoCTF{l3arn_th3_r0p35}```
