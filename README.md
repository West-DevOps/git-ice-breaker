# git-ice-breaker
A rough and ready guide to using (and abusing) git.

## So what are we doing here? 

This guide will attempt to take someone who has 0 `git` experience and while it won't make you a hero it will give you
enough information and exercises to be comfortable using git in your projects and for sharing code with the wider world. 

## Getting started (installing)


## Some concepts 

First we will go over some of the fundamental concepts that having a grasp of will allow you to quickly grasp `git` at
large... 

### The repository 

This is the top-level directory of a git repo, it will always have a `.git` directory in it and this is where `git` stores
the information required to build the entire history of the repository.  Every file ever created, changed, renamed or 
deleted.  It is all in the `.git` directory here!  We never go in and edit any files in the `.git` directory directly.  
But it is worth knowing that you entire change log for the repository lives here (i.e. don't delete it!).

Repositories will also have something commonly referred to as the `clone url`.  This is either a `ssh` ot `https` link.

The clone URLs for this repository are: 
* `git@github.com:West-DevOps/git-ice-breaker.git` for `SSH`
* `https://github.com/West-DevOps/git-ice-breaker.git` for `HTTPS`

You can find the clone URLs for any repo on the repo homepage under the green "Code" button: 
![Git Clone](./assets/git_clone.png)

### Workflows 

Different developer teams will have different git workflows, these are usually defined and refined by teams as they 
find what works for them.  If you are starting out from scratch then you should probably familiarise yourself with 
some of the common workflows you can expect to find in projects using `git`:

* [The Github Flow](https://docs.github.com/en/get-started/using-github/github-flow) The standard for open source github hosted projects
* [Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows) Good comparison from atlassian on a few
* [Git Workflows](https://git-scm.com/docs/gitworkflows) the OG.  Not used all too often anymore.

Ultimately, there is no single "right" answer or silver bullet when choosing (or switching) workflows.  Just pick the 
one that you think will work for your project and if it does not just pick another one and start doing that instead!
One of the beauties of git is that you are never bound to a single workflow once you pick it so live dangerously, 
commit direct to `main` for a while until you completely knobble your repo and realise that changing the `main` branch
directly is probably not the best workflow on earth! 

Good job you can `revert` changes in git! 

### Staging

One of the core concepts of `git` which comes up often as a trap for new gamers is the `stage`.  This is; put simply 
the changes you are making that will be `committed` when you call `git commit`.  As an example: 

Let's say we create two files in the repository, `a.txt` and `b.txt`:
```shell
touch a.txt b.txt
```


## Your first commit

Now we have covered installing `git` and some of the core concepts, let's make a basic change to this repo! 

### Cloning repositories 

### Creating a branch 

### Checking out a branch 

### Making changes 

### Staging changes

### Checking status of the change 

### 

## External Resources

* [The git book](https://git-scm.com/book/en/v2) this is the bible of `git`.  It is _the_ reference on git.  
  * It is also a hard read for anyone new to git.
* [Oh Shit Git!](https://ohshitgit.com/) a tongue in cheek look at some of the more esoteric use-cases of git. 
  * This will get you out of hot water quite often! 
* 
