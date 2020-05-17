---
title: Password Generator
---

# Password Generator
This program helps users create unique, strong passwords for use in any account. While it doesn't have it's own interface, I've built it into the Password Manager's creation scheme. How it works is simple; if a user wants to create a password, all they have to do is click "Create" with the password field empty and the password will be stored along with the rest.
The technical details of the project are also pretty simple. As of right now, all this script does is generate a sequence of 12 random characters, ranging from letters to special. Then, it assigns the service a random seed, which is used to generate the values for a cipher. The original password is run through **three** ciphers, each different from the last. Finally, some characters are added, the new phrase is run through all three ciphers again, and your phrase is now secured for storage. The idea is to create as many degrees of separation between the phrase you use to login, and the phrase that is stored, so that anyone trying to get into your account will have a difficult time of it even if they access your passwords.
Stay safe!
