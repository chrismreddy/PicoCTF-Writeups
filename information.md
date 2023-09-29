# information

## Overview

Points: 10
Category: Forensics

## Description

Files can always be changed in a secret way. Can you find the flag? cat.jpg

## Hints

1. Look at the details of the file
2. Make sure to submit the flag as picoCTF{XXXXX}

## Approach

I used this website in order to see if there were any plaintext strings embedded in the image: https://29a.ch/photo-forensics/#strings

The resource element looks like it's in base64 format. I attempted to decode it at the following website: https://www.base64decode.org/

This led me to the flag.

## Flag

picoCTF{the_m3tadata_1s_modified}
