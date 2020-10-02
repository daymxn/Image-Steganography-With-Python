# Overview

Image steganography is the process of hiding information within an image. This program is utilized to hide a text based message within an image. 

# Why Used

When I first (seriously) got into python my freshman year, one of the first projects I made was a hacky image steganography program. I recently went through my school HDD, and got the idea to remake it for fun. So low and behold; here is my remade image steganography program :)

## How-To-Use

Just load up `ImageSteganography.py` and execute it.
- Place whatever images you want to encrypt a message into, inside the `/encrypt` sub directory.
- Place whatever images you want to decrypt a message into, inside the `/decrypt` sub directory.
- Any images encrypted with the program will be replicated and saved into the `/export` sub directory.

The program will work with **multiple** images, so if you place multiple images within a sub directory, it'll work with all of them. It also recognizes the file extension, so if you have a bunch of text files within a sub directory it'll just ignore them.

## Limitations Of This Program
- This progam was developed in `Python 3.0`, although it **should** work with `Python 2.7`, but I haven't gotten around to testing it yet.
- This program will **ONLY** work with PNG images. JPEG images have a specific compression issue that screws with the encryption algorithim.
- You can only encrypt a specific amount of characters within an image. The exact amount is based off the size of the image (one pixel is dedicated to each character).
