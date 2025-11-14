# Raspberry Pi Jammer

## How It works
Using raspberry pi to create a deauthentication attack at targeted devices connected to a network. We can essentially "trick" the wifi router to disconnect the target by
sending fake deauth packets to the targeted device as the wifi router. We can then continue to send out these deauth packets to continuously keep the device disconnected from the wifi. 

## Team members
- Vanessa Valdes - Research and development - Github: @vasliro

## Setup Instructions
1. On kali linux, go to the route directory
2. Make a new directory for your jammer then go to said directory
3. create a python file for your code
4. Enter code and run the script

## Technologies Used
- Kali Linux
- SD card
- raspberry pi
- USB Wifi Adaptor
- python
- scapy

## Project structure
Our main consists of a:
- README.md, which has a basic overview of the project.
- .gitingore, which contains files that git will be ignoring.
-  src folder, which contains copies of the code used
-  assets, which contains images and videos of our project =

## How to Contribute
Team members can contribute by researching the inner workings and usages for a fully operational rasp pi wifi jammer, setting up and running programs to test our prototype, and keeping track of new developments as we approach a final product.

## Current Status
Researching how to implemeent deauth attacks with raspberry pi and set up of software while we wait for the single board computer to arive.

## License
MIT License

Copyright (c) 2025 No-Brainers

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
