# Bandit Level 4 -> Level 5

# Challenge:

 I can use cat command to view each files .however, not very efficient when we deal with more files.

# Solution:

bandit4@bandit:~/inhere$ file ./*

./-file00: data
./-file01: OpenPGP Public Key
./-file02: OpenPGP Public Key
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data

bandit4@bandit:~/inhere$ cat ./-file07

bandit4@bandit:~/inhere$ cat ./-file07

4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

# Explanation :

Instead using file  "File ./filename@ let's use the wildcard *

Password:4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
~ What I have learned :
Use the wildcard *
