# Bandit Level 13 -> Level 14

# Challenge: download sslkey.private file into my local machine

# Solution:

 ssh bandit14@bandit.labs.overthewire.org -p 2220 -i .\sshkey.private 'cat /etc/bandit_pass/bandit14'

MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

# Explanation: 

Use the private key in the home directory to logon in

Password: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

# What I have learned:

 SSH command to connect another machine