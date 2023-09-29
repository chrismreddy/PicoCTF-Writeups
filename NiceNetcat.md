# Nice Netcat...

## Overview

Points: 15
Category: General Skills

## Description

There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 7449, but it doesn't speak English...

## Hints

1. You can practice using netcat with this picoGym problem: what's a netcat?
2. You can practice reading and writing ASCII with this picoGym problem: Let's Warm Up

## Approach

I ran the nc mercury.picoctf.net 7449 command, and it gave me a stream of numbers.

I realized these numbers are most likely ASCII values for text. I used an online source to decode the data: https://www.duplichecker.com/ascii-to-text.php

This gave me the flag value.

## Flag

picoCTF{g00d_k1tty!_n1c3_k1tty!_f2d7cafa}
