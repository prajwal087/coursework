﻿# coursework
Me:
As a student i was blessed to get a project which was fun to work on my Idea was to create something I really need, that I can trust and it can be flexible. The first project has made for the terminal, but I had fun to learn how to export a python script to the GUI version.

Why PyPWD:
As Security Officer I cannot trust to save all my passwords to a KeyManager or to an external Password Manager, because I don't know if my passwords are transmitted via the internet or in the future we'll there a bulletin with some exploit then I have to re-change all my passwords. I think is better to combine my basic python skills with what I need, then I created my own password manager, in Python3, with encryption based of random KEY and Password, and sure that it hasn't an internet connection.

Requirements:
Tested on a MacOSX, working also in Linux

Python3

Pandas

cryptography

pyAesCrypt

PyQt5

How Works:
First Run: PyPWD > Creates Master Key with your master username and password (Do not forget it or modify the configfile, otherwise you'll be not able to open your password manager anymore).

PyPWD > Saves a DataFrame as an encrypted CVS and all passwords are the encrypted too, with key and the master password.

Login: PyPWD > Dencrypts the password file, based of the username and password filled.

Features
Search Password

Show All Password

Copy the table cell content via double-click

Create New Password + random creation button

Delete password

Config Language

Config Encoding

Export all cleaned password in excel

Export encrypted backup for PyPWD

Import encrypted backup for PyPWD

Reset all password

Change master password

