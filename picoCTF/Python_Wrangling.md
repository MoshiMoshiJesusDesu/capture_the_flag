# Python Wrangling

## Problem
[Challenge](https://play.picoctf.org/practice/challenge/166)

## Solution

- Download all the necessary files for the challenge
```
wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/ende.py
wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/pw.txt
wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/flag.txt.en
```
- Upon running `ende.py`, it asks for a file to decrypt.
- And looking at the code in ende.py, it asks for a password when one tries to decrypt a `flag.txt.en`.
```
python ende.py -d flag.txt.en < pw.txt
```
