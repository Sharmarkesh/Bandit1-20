# Bandit Level 9 -> Level 10

# Challenge: 

Understanding strings options in man page
# Solution:

bandit9@bandit:~$ ls

data.txt

bandit9@bandit:~$ strings data.txt | grep '='

========== the
9=H`
[!#=Z
========== password
xWf=
f\Z'========== is
e=i{\#
/1=s
nS=F
M=Sl
=LGT
y =1
========== FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
'+Y=+


# Explanation :

Use strings command to print out all human readable strings of a file

Password: 

FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

# What I have learned: 

The use of strings command 
