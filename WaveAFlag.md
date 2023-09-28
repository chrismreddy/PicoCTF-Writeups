# Wave A Flag

## Overview

Points: 10
Category: General Skills

## Description

Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

## Hints

1. This program will only work in the webshell or another Linux computer.
2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/beec4f433e5ee5bfcd71bba8d5863faf/warm
3. Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm
4. -h and --help are the most common arguments to give to programs to get more information from them!
5. Not every program implements help features like -h and --help.

## Approach

The first thing I did was use the wget tool to download the "warm" program.

After that downloaded, I had to change the file's permissions so it was executable. (chmod +x warm)

I tried to execute the file by running the command ./warm, and it prompted me: "Hello user! Pass me a -h to learn what I can do!"

I then ran the command ./warm -h and received the flag.

## Flag

picoCTF{b1scu1ts_4nd_gr4vy_616f7182}
