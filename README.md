# Bandit Level 8 -> Level 9

# Challenge: 

A bit difficult but i had to sue uniq man page to figure out

# Solution:

bandit8@bandit:~$ ls

data.txt

bandit8@bandit:~$ sort data.txt | uniq -u

4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

# Explanation: 

The -u flag makes uniq print only unique strings

# Password:
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
# What I have learned: 
sorting by uniq command and its options