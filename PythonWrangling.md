# Python Wrangling

## Overview

Points: 10
Category: General Skills

## Description

Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?

## Hints

1. Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/ende.py
2. $ man python

## Approach

Downloaded the script into the shell by using the wget command. The name of the script is ende.py.
When I ran "python ende.py" the following line returns:
Usage: ende.py (-e/-d) [file]
It looks like -e is the switch for encrypt, and -d is the switch for decrypt.
So, running python ende.py -d flag.txt.en and putting in the provided password gives us the flag.

## Flag

picoCTF{4p0110_1n_7h3_h0us3_192ee2db}
