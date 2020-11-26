## strings it
### Category
General Skills
### Problem
Can you find the flag in [file](./misc_files/strings) without running it?
### Hints
1) [strings](https://linux.die.net/man/1/strings)
### Solution

**STEP 1**

Since we're trying to find the flag without running the file, we need to use the command line interface (CLI).

**STEP 2**

Change your directory to wherever the ```strings``` file is, using ```cd```. For this documentation, ```strings``` is in the ```misc_files``` folder.

**STEP 3**

In the CLI, type in ```strings strings | grep -i picoctf```

The terminal gives us the string "picoCTF{5tRIng5_1T_827aee91}".

Thus, we have the flag:

```picoCTF{5tRIng5_1T_827aee91}```
