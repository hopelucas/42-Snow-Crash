# 42-Snow-Crash

*This project is an introduction to computer security. Snow Crash will make you discover security in various sub-domains, with a developer-oriented approach. You will become familiar with several languages (ASM/perl/php…), develop a certain logic to understand unknown programs, and become aware of problems linked to simple programming errors.*

## Concept

In Snow-Crash, you're navigating around inside the file system of a virtual machine to find "flags", or tokens that act as passkeys. Once you find a flag for a level, you can navigate to the next level. Passkeys can be hidden inside files, packets, functions etc - and you'll have to use a variety of different methods (and some creative thinking) to get to the flags.

There are 14 levels in total, or 10 if you're not doing bonuses. (I'd recommend doing bonuses, as it'll provide some useful knowledge in lower-level machine languages).

Some methods are more intuitive than others. I've tried to include the methods I found required the least work outside of the terminal, so you can follow my process without needing to copy paste as much as possible.

Good luck! :D

## Set Up
You're provided the iso image, but the specs I recommend in setup are as follows:
- Oracle (64-bit)
- 1024MB Memory
- Network Access **bridge** (this assists with weird setup network problems)
- Port 4242
- Name it 'SnowCrash'
- If in school, create the files in the /sgoinfre/, so you can move computers where needed
- VirtualBox, for accessible features

For one of the flags, you'll also find it handy to have a second VM set up:
- Debian (64-bit)
- 2048MB Memory
- Network Access **bridge**

For best results, you should SSH into the VM through your iterm:

`ssh level00:VM_IP -p 4242`, replacing VM_IP with the relevant IP address of the VM.

I'd also recommend you keep a notepad / Word document to record tokens and processes.

## Useful Programs

## Contents
