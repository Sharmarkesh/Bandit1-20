# Bandit Level 2 -> Level 3
The password for the next level is stored in a file called spaces in this filename located in the home directory
# Challenge:
Running cat spaces in the filename will cause errors as it will think each word in spaces in the filename is its own separate file.

bandit2@bandit:~$ cat '--spaces in this filename--'
cat: unrecognized option '--spaces in this filename--

bandit2@bandit:~$ cat "--spaces in this filename--"
cat: unrecognized option '--spaces in this filename--'

# Solution:
bandit2@bandit:~$ cat -- "--spaces in this filename--"

MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
# Explanation:
Running cat --spaces in the filename-- will cause errors .
# Password: 
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
# What I have learned:
 Using spaces in filenames are generally to be avoid in Linux