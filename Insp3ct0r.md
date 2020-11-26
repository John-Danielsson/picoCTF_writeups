## Insp3ct0r
### Category
Web Exploitation
### Problem
Kishor Balan tipped us off that the following code may need inspection: https://jupiter.challenges.picoctf.org/problem/41511/ [(link)](https://jupiter.challenges.picoctf.org/problem/41511/) or http://jupiter.challenges.picoctf.org:41511
### Hints
1) How do you inspect web code on a browser?

2) There's 3 parts
### Solution

**STEP 1**
Click on one of the provided links to get started.

**STEP 2**
Inspect the source code of the website by right clicking on the site and choosing to view the source code. 

**STEP 3**
In the HTML document, we can find a comment giving us part 1 of the flag:

```<!-- Html is neat. Anyways have 1/3 of the flag: picoCTF{tru3_d3 -->```

**STEP 4**
In the CSS document, we can find a comment giving us part 2 of the flag:

```/* You need CSS to make pretty pages. Here's part 2/3 of the flag: t3ct1ve_0r_ju5t */```

**STEP 5**
In the JS document, we can find a comment giving us part 3 of the flag:

```/* Javascript sure is neat. Anyways part 3/3 of the flag: _lucky?832b0699} */```

Thus, we have the flag ```picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699}```.
