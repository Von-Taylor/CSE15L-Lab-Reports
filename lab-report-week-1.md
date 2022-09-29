# Week 1 Lab Report (Getting Started)

**Steps that will be Covered:**
> 1. Installing VScode
> 2. Remotely Connecting
> 3. Trying Some Commands
> 4. Moving Files with scp
> 5. Setting an SSH Key
> 6. Optimizing Remote Running


## 1. Installing VScode
## 2. Remotely Connecting
![Connecting-to-ieng6](Week-1-Lab-Reports-Pics/Remotely-Connecting.jpg)
- In this step, I connected my local personal computer to the remote ieng6 server by using the Secure Shell (ssh) program
- I did this by using the "ssh <*cs15lUsername*>@ieng6.ucsd.edu"
- If it's your first time doing this, you may have to answer "yes" to authorize and enter your cs15l password

## 3. Trying Some Commands
![Trying-Commands](Week-1-Lab-Reports-Pics/Trying-Some-Commands.jpg)
- While on the ieng6, I used different different variations of the "ls" commands, but all of them essentially list out the files inside of a directory
- I also used the "cd" command, where I copied the 'hello.txt' file inside the '/home/linux/ieng6/cs15lfa22/public' folder to the the home directory, which is denoted by the '~'
- In the last line, I used the "cat" command to print the contents of the hello.txt file

## 4. Moving Files with scp
![Using-SCP](Week-1-Lab-Reports-Pics/SCP.jpg)
- I started off in the ieng6 to show that I had a 'hello.txt' file in its home directory
- I then exited it and used the "scp" to do a secure copy of the 'hello.txt' file from the ieng6 to my home directory on my local personal computer
- I then used the "ls" command to list out the files on my local personal computer (the copied hello.txt file is shown on the very right side of the terminal) 

## 5. Setting an SSH key
![SSH-Key](Week-1-Lab-Reports-Pics/SSH-Key.jpg)

## 6. Optimizing Remote Running
