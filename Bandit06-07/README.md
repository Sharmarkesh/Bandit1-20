# Bandit Level 6 -> Level 7

# Challenge: 

Again using find command the previous level ( size, user, group, type)

find / -size 33c -user bandit7 -group bandit6 -type f

The above command print , additional permission denied output.

# Solution:

bandit6@bandit:~$ find / -size 33c -user bandit7 -group bandit6 -type f 2>/dev/null
/var/lib/dpkg/info/bandit7.password

bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password

morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

# Explanation :

Use dev/null to hide all other errors message

Password:

morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

# What I have learned :

Find command and hide unnecessary output using /dev/null