#Bandit Level 3 -> Level 4
Files that start with . are hidden
# Challenge:  To list hidden files, use ls with -a flag. Read ls --help to know more

# Solution:
Use ls -a and cat the hidden file

bandit3@bandit:~/inhere$ ls
bandit3@bandit:~/inhere$ ls -a
.  ..  ...Hiding-From-You
bandit3@bandit:~/inhere$ cat .
./                  ../                 ...Hiding-From-You
bandit3@bandit:~/inhere$ cat ..
../                 ...Hiding-From-You
bandit3@bandit:~/inhere$ cat ...Hiding-From-You
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

# Explanation
Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
# What I have learned:
 Use ls -a to show any hidden file