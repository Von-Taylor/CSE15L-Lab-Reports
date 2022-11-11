# Lab Report Week 7
- **HTML Link:** [https://von-taylor.github.io/cse15l-lab-reports/lab-report-week-7.html](https://von-taylor.github.io/cse15l-lab-reports/lab-report-week-7.html)

## Part 1 Chosen Task:
- In `DocSearchServer.java`, change the name of the `start` parameter of `getFiles`, and all of its uses, to instead be called `base`.

Key Strokes:
  > `/star<Enter>cebase<Esc>n.n.:wq<Enter>`
  >
  > Screenshot of `/star<Enter>`:
  > ![1](Week-7-Lab-Report-Pics/1.jpg)
  > 
  > Screenshot of `cebase<Esc>`:
  > ![2](Week-7-Lab-Report-Pics/2.jpg)
  > 
  > Screenshot of `n.`:
  > ![3](Week-7-Lab-Report-Pics/3.jpg)
  > 
  > Screenshot of `n.`:
  > ![4](Week-7-Lab-Report-Pics/4.jpg)
  > 
  > Screenshot of `:wq<Enter>`:
  > ![5](Week-7-Lab-Report-Pics/5.jpg)

## Part 2 scp vs vim:
- scp procedure: make the edit to `TestDocSearch.java`, scp it over to the remote server, ssh into the remote server, cd into the right\
directory, and then run `bash test.sh`
  > Time elapsed: 01 minute 19 seconds

- vim procedure: ssh into the remote server, cd into right directory, vim into `TestDocSearch.java`, make the edit, exit\
`TestDocSearch.java`, and then run `bash test.sh`
  > Time elapsed: 00 minutes 38 seconds

- Verdict: it is much easier and faster to ssh into the remote server and then make the edits directly into there. Although this time\
comparison doesn't seem that extravagent, making edits directly on the server is exceedingly much better when you have to make edits\
to multiple different files, maybe in different directories, instead of having to consume time just to locally scp each file to their\
respective directory on the remote, and then only then, being able to go back onto the server to run them.
