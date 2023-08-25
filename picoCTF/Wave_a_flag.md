# Wave a flag

## Problem
[Challenge](https://play.picoctf.org/practice/challenge/170)

## Solution
- Download the binary executable.
```
$ wget https://mercury.picoctf.net/static/cfea736820f329083dab9558c3932ada/warm
```
- Try to run the binary but it won't have the permission to execute. Give it the execute permission using `chmod`.
```
$ ls -al warm
$ chmod +x warm
```
- Run the binary. It will ask you to use the `-h` flag to know more about the binary. That should print the flag.
```
$ warm
$ warm -h
```
