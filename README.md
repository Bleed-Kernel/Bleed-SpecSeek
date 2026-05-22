
![Logo](https://i.imgur.com/Zg37VpH.png)
# SpecSeek v5. All in One Specification Tool

A soloution to finding everything there is to know about a computers specifications. all in one elegant location. **a great way to share your device specifications support and features**. not sure if your PC supports some functionality? SpecSeek will relay that to you.

## Contributing
Contributions in any way are always welcome, if its porting to your own operating system or making a PR for me to review, I welcome all sorts of contributions and intergration. when porting I would appreciate it if your build script pulls directly from this repo to keep your build of specseek up to date as its still in active development.

**When contributing please try follow the naming standard used already, and do not add repeat functionality. please keep a simple codebase as a priority.**
## Build & Run from Source
to build the ELF executables use the following command
``` bash
make
```
however to create the Windows Executables use the following command
``` bash
make windows
```

## Create your own version of SpecSeek
the backend of specseek that parses all the information is libspecseek, you can use this to create your own client or just use it as a library to identify CPU support. It is a powerful tool! and its free [check it out here](github.com/Mellurboo/libspecseek)
