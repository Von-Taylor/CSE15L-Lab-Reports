# Lab Report Week 5
## Linux Commands to Inspect:
- less: similar to 'cat' command, except allows you to have all the contents of the file on 1 screen instead of just on the terminal.
- find: recursively lists all the relative paths of the files in a directory and its subdirectories onto the terminal.
- grep: accepts a string argument, in which it searches a file and prints all lines in it that have the given string.

    >   (All of this is done with text files inside the technical/biomed directory on a file called 'rr74.txt')

### 3 Interesting Command-Line Options for "less"
1. -N command
    > `less -N rr74.txt`
    
    > Output:
    > ![lessN](Week-5-Lab-Report-Pics/lessN.jpg)
    > - What this command does is **display the line numbers** in the file that you open with the 'less' command. This is useful\
    > for quality-of-life purposes where you might want to know where you inside of a file that you are reading.

2. -p command
    > `less -p<string> rr74.txt`
    > - \<string> is any string the user wants to input
    > - (For the output, I choose my \<string> to be "med")
    
    > Output:
    > ![lessp](Week-5-Lab-Report-Pics/lessp.jpg)
    > - What this command does is tells 'less' to **start at the first instance of "med"** in the file. This is also useful for\
    > quality of life purposes where you may want to start reading the file from a string that of your choosing.
    
3. -z command
    > `less -z<number> rr74.txt`
    > - \<number> is any positive integer the user wants to input
    > - (For the output, I choose my \<number> to be 5 and press 'space' on my keyboard once)
    
    > Output:
    > ![lessz](Week-5-Lab-Report-Pics/less-z.jpg)
    > - What this command does it makes it so that when you press 'space' on your keyboard while in the 'less' screen of your file,\
    > the screen will only move down 5 lines instead of 1 entire screen down.

### 3 Interesting Command-Line Options for "find"
1.
2.
3.

### 3 Interesting Command-Line Options for "grep"
1.
2.
3.
