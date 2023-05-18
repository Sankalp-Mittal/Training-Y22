# Linux Commands Tutorial

# Level 0:

Used command ssh bandit0@bandit.labs.overthewire.org -p 2220

# Level 0-1:

Used cat readme to get password

Password : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

ssh bandit1@bandit.labs.overthewire.org -p 2220

along with the new password

# Level 1-2:

Used cat ./- to get password

Password : rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

ssh bandit2@bandit.labs.overthewire.org -p 2220

# Level 2-3:

cat "spaces in this filename"

Password : aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

ssh bandit3@bandit.labs.overthewire.org -p 2220

# Level 3-4:

cd inhere

ls -a

cat .hidden

Password : 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

ssh bandit4@bandit.labs.overthewire.org -p 2220

# Level 4-5:

cd inhere

check all cat ./-file0x

password is in -file07 : lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

ssh bandit5@bandit.labs.overthewire.org -p 2220

# Level 5-6:

cd inhere

find . -type f -size 1033c ! -executable

output is ./maybehere07/.file2

cd maybehere07

cat .file2

Password : P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

ssh bandit6@bandit.labs.overthewire.org -p 2220

# Level 6-7:

find / -user bandit7 -group bandit6 -size 33c 2\>/dev/null

/ =\> Root

2\>/dev/null =\> do not show error messages

Password : z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

ssh bandit7@bandit.labs.overthewire.org -p 2220

# Level 7-8:

grep "millionth" ~/data.txt

grep gives all lines containing specified string

Password : TESKZC0XvTetK0S9xNwm25STk5iWrBvP

ssh bandit8@bandit.labs.overthewire.org -p 2220

# Level 8-9:

sort data.txt | uniq -u

EN632PlfYiZbn3PhVK3XOGSlNInNE00t

ssh bandit9@bandit.labs.overthewire.org -p 2220

# Level 9-10:

cat data.txt | strings | grep "=" this will first take all human-readable commands and then find ones with =

G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

ssh bandit10@bandit.labs.overthewire.org -p 2220

# Level 10-11:

base64 -d data.txt

Output :

The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

ssh bandit11@bandit.labs.overthewire.org -p 2220

# Level 11-12:

cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

The password is JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

ssh bandit12@bandit.labs.overthewire.org -p 2220

# Level 12-13:

![](RackMultipart20230518-1-zc37qq_html_6a4bc9717a17dc71.png)

![](RackMultipart20230518-1-zc37qq_html_6c6edaff76140789.png)

The password is wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

ssh bandit13@bandit.labs.overthewire.org -p 2220

# Level 13-14:

ls

sshkey.private

ssh bandit14@localuser -i sshkey.private -p 2220

# Level 14-15:

cd /etc/bandit\_pass

cat bandit14

Password : fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

Disconnect and login using the credentials

..
