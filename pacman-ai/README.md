# AI 인공지능
See Midterm and Final Project:
https://sites.google.com/hanyang.ac.kr/2021ai


## Getting Started
The projects for this class assume you use Python "2.7". You may use Linux, Windows 10, or Mac OS.

If you run Windows 10, install Ubuntu by following this:

https://ubuntu.com/tutorials/tutorial-ubuntu-on-windows#1-overview

You need to set up the sudo password.

```console
$sudo apt update
$sudo apt install python2.7 python-pip
$sudo apt install unzip zip vim git
```

If asked, please enter sudo password.
Install and run Xming

https://sourceforge.net/projects/xming/files/latest/download 

Set the display forwarding

```console
$export DISPLAY=localhost:0.0
```

clone project files
Download project files through git clone (try to learn git:  https://rogerdudler.github.io/git-guide/index.ko.html)

Throughout project, try to commit your changes by git commit -m "change message" so we can track your changes (at least for each task)

```console
$git clone https://github.com/leeymcj/pacman-ai.git
$cd pacman-ai
```
You should be able to play a game of Pacman by typing the following at the command line (note the left key is a right key is d) : 

```console
$python2.7 pacman.py
```

We will develop an intelligent agent (Alpha-Pacman) that plays Pacman for us.

## Submission

zip entire project files including git log
```console
$zip <MyName>.zip -r * .git
```
then, upload <MyName>.zip to LMS homework submission.



