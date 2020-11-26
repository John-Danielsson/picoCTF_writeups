## where are the robots
### Category
Web Exploitation
### Problem
Can you find the robots? https://jupiter.challenges.picoctf.org/problem/36474/ ([link](https://jupiter.challenges.picoctf.org/problem/36474/)) or http://jupiter.challenges.picoctf.org:36474
### Hints
1) What part of the website could tell you where the creator doesn't want you to look?
### Solution

**STEP 1**

Most websites have a ```robots.txt``` page, which can be accessed by appending ```robots.txt``` to the URL of the page that you are on. Make sure that there is a ```/``` immediately before ```robots.txt``` (but don't have two ```/```s before ```robots.txt```).

**STEP 2**

At the URL ```https://jupiter.challenges.picoctf.org/problem/36474/robots.txt```, we find the following text:

User-agent: *

Disallow: /477ce.html

*NB: The robots.txt file is a set of instructions for search engine crawlers telling them which pages they can or can't request from your site. It's used mainly for preventing a site from getting overloaded with requests.*

**STEP 3**

Now we can replace ```robots.txt``` with ```477ce.html``` in the foregoing URL. When we do so and load the URL ```https://jupiter.challenges.picoctf.org/problem/36474/477ce.html```, we get the following text:

![The image isn't displaying, so I'll just tell you the flag here: picoCTF{ca1cu1at1ng_Mach1n3s_477ce}](./img/robots_img.png "ROBOT ROCK")

Thus, we have the flag:

```picoCTF{ca1cu1at1ng_Mach1n3s_477ce}```