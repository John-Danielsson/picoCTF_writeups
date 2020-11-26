## logon
### Category
Web Exploitation
### Problem
The factory is hiding things from all of its users. Can you login as logon and find what they've been looking at? https://jupiter.challenges.picoctf.org/problem/15796/ ([link](https://jupiter.challenges.picoctf.org/problem/15796/))] or http://jupiter.challenges.picoctf.org:15796
### Hints
1) Hmm it doesn't seem to check anyone's password, except for logon's?
### Solution

**STEP 1**

No matter what credentials we use, we are able to log in, but we are taken to a page with a pop-up that says: "Success: You logged in! Not sure you'll be able to see the flag though." It's possible that there is a cookie storing a variable that prevents us from seeing the flag... 

**STEP 2**

Sure enough, if we check out the cookies for the URL ```https://jupiter.challenges.picoctf.org/problem/15796/flag``` (this is the page we get to after logging in), we can see that the value "Admin" is set to "False". If we can change that to "True" and refresh the page, we get the following text: picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}.

Thus, we have the flag:

```picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}```