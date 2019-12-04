# GitHub Tutorial

_by Fernando Garcia_

---
## Git vs. GitHub
#### Git
Git allows you to do version control on your IDE and does not require a connection to the internet. Version control is the ability to save certain parts of your code or all of it if you want to. The best part of git is that it allows you to only revert a certian part of your code and keep everthing else that you currently have.  
#### GitHub
Stores code in the cloud and visually keeps track of code. GitHub also alows you to colaborate with others in multiple ways. One of the many things github allows is cloning which copies the code from a repo to your local. An alternative to this is forking which rather than just getting a copy of the repo, it makes an entirely seprate repo on github and allows you to push changes to that seprate repo. Repositories on github are called remotes.

---
## Initial Setup
#### Set up GitHub account
To set up a github account just follow these easy steps!
   1. go to [Github.com](https://github.com/)
   2. click the sign up botton in the top right corner
   3. enter a username (if an hstat student you can use the beginning of your hstat email.)
   4. enter your email address (if an hstat student use your hstat email)
   5. enter your password, this can be whatever you want.
   6. verify your account 
   7. then select a plan, no payment needed as there is a free option.
#### Set up IDE
here is an easy guide to set up your IDE  
[(_click this link for the guide_)](https://github.com/hstatsep/ide50)


---
## Repository Setup
to set up a repository all you need to do is follow these steps.
   1. make a new directory using the `mkdir` command into your command line
   2. use the `cd` command to get inside the new directory you just made
   3. then use `git innit` 
   4. after you initialize your directory it is now a repository able to use git. 
   5. now make a file using `touch` 
   6. after you make the file you can use `git add .`
   7. then you can use `git commit -m`, after the -m add quotations to add a message.
and that's it! you've now set up a repository.

---
## Workflow & Commands
Now that you are using git and github here are some useful commands that will help you out when doing work.
#### git status
git status will tell you if you've made any changes or not. If a file is in red that means that you've made a change to it or you haven't added it yet. If the file is in green it means you have already added it and is ready to be commited.
#### git add
When you use git add it sets up a file to be commited. The only things that will be commited are things that you have added. 
#### git commit
Git commit takes a snapshot of code that you have added using git add. This means when you use `git log` you'll be able to look at past commits and reverse any changes you've made. 
 
---
## Rolling Back Changes
