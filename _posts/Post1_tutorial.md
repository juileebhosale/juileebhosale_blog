## Github for babies

### How to be not scared shell coding

If you are also in a coding occupation like me but get the mini panic attacks when someone mentions "bash commands" or "Linux" and don't know what the hell that Github app is and why can't I find it on app store - welcome this tutorial is for you!

![Screen Shot 2022-08-20 at 5 45 47 PM](https://user-images.githubusercontent.com/42019236/185770541-c2c22314-4d85-4495-ad24-d7095bb5b542.png)


### What is Github
First things first let's start with by understanding what is Github and why you see every coder talk about it. In the most simplest words, Github is nothing but a sophisticated version control tool - kinda like Google docs for coders.

Imagine this - you and another coder are working on the same code file but own different aspects of the code. You both work started working on a code which had 10 lines initially but you deleted line 2 and added 3 new lines. Meanwhile your colleague changed line 3 and added some of his code.
Now it's time to put the code together in one. But uh oh, your colleague will have completely different code file than you.
You compare both the files manually and realise line 2 is missing in one code while line 3 has changed in another.
But imagine doing this when there are thousands and thousands of lines of code!! That's not pratically possible
That's where Git control comes in and solves this problem.

### Getting started
Before we jump into the fun stuff - here's a quick overview of some common Git terminology

* **Repository** - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. 
* **Branch** - A branch is a parallel version of a repository. Think of it like a copy of your main branch or main code file. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch.
* **Commit** - A commit, or "revision", is an individual change to a file (or set of files). Think of it as pressing save. Commits usually contain a commit message which is a brief description of what changes were made.
* **Push** - To push means to send changes made to your local code to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them. There are standard processes and commands to push changes and we'll go through them in the later section
* **Pull** - Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
* **Merge** - Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line


