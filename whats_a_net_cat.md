## what's a net cat?
### Category
General Skills
### Problem
Using netcat (nc) is going to be pretty important. Can you connect to jupiter.challenges.picoctf.org at port 64287 to get the flag?
### Hints
1) nc [tutorial](https://linux.die.net/man/1/nc)
### Solution

**STEP 1**

The link in the hint tells us this:

*"The nc (or netcat) utility is used for just about anything under the sun involving TCP or UDP. It can open TCP connections, send UDP packets, listen on arbitrary TCP and UDP ports, do port scanning, and deal with both IPv4 and IPv6. Unlike telnet(1), nc scripts nicely, and separates error messages onto standard error instead of sending them to standard output, as telnet(1) does with some."*

Here's the [Wikipedia article on ports](https://en.wikipedia.org/wiki/Port_(computer_networking)).

**STEP 2**

In your CLI, type in ```nc jupiter.challenges.picoctf.org 64287``` to get the following text:

```
You're on your way to becoming the net cat master
picoCTF{nEtCat_Mast3ry_284be8f7}
```

Thus, we have the flag:

```picoCTF{nEtCat_Mast3ry_284be8f7}```