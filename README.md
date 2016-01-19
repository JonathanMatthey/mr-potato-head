#Project 1: Mr. Potato Head

![Imgur](http://i.imgur.com/Vy06FW3.gif)

## Before Class

### Teacher Preparation
The lead teacher must clone this repository before the start of class. Students will be forking from your repo.
### Daily Objective

Students will understand the basics of version control. They will be able to setup an account on Github and perform the `fork` `clone` and `push` operations.

### Key Points

* **Git** is an example of a version control software.
* **GitHub** is a service that lets programmers use **Git** to store their work on cloud-based servers. 
* **GitHub** is widely used in the industry for collaboration.

### Assessment

1. Write the Exit Ticket based off [assessments from current lesson](assessments/).

Students will show progress toward reaching the objective based on their performance on the Exit Ticket quiz.

### Vocabulary

* Version control
* Git
* Github
* Repository (repo)
* Clone
* Push
* Pull
* Fork
* Merge
* Stage
* Commit

### References
* [Presentation Slides](https://docs.google.com/presentation/d/1eH0T3ESKY7AJQjtAL7_X4-uWqJRXwgKGguoAbmQmzRw/edit?usp=sharing)
* http://gitref.org/basic/
* https://try.github.io/levels/1/challenges/1
* http://en.wikipedia.org/wiki/Revision_control
* http://en.wikipedia.org/wiki/Git_(software)
* http://git-scm.com/docs/git-merge

## During Class

### Do Now

1. Attendance
2. Return reviewed Exit Ticket from the previous class.
3. The Do Now can be found on slide 1 of the [Presentation Slides](https://docs.google.com/presentation/d/1eH0T3ESKY7AJQjtAL7_X4-uWqJRXwgKGguoAbmQmzRw/edit?usp=sharing).

### Opening

Today, we will learn about collaboration through the use of **Git** and **GitHub**. 

The opening lecture can be found on slides 2-4 of the [Presentation Slides](https://docs.google.com/presentation/d/1eH0T3ESKY7AJQjtAL7_X4-uWqJRXwgKGguoAbmQmzRw/edit?usp=sharing).



### Introduction to New Material ("I Do")

During this "I Do" lecture, the teacher is going to demonstrate forking a repo on pushing any changes using the terminal.

##### (1) Locate the repo.

Find the **repository** you are looking for by searching its name or username of the owner in **GitHub**.

A **repository** (or repo) is a place where we store our code.

##### (2) Fork the repo.

**GitHub** allows us to **fork** the repo by simply clicking the **`Fork`** button in the top-right corner of any repository.

##### (3) Clone this repo into your own Cloud9 account workspace.
1. Copy the "Clone URL" from this **repo**.
2. In your Cloud9 dashboard, click on the "Create New Workspace" button and paste the URL you just copied to your clipboard.


##### (4) Add the code assigned to you.
For this project, I am going to add the arms to Mr. Potato Head in the potatohead.html file.


##### (5) Add.

A **`push`** is an action to upload the work saved on your Cloud9 to your GitHub repo.

First, we make sure that our changes were completed properly. We do this by using the `git status` command.

**Git** has detected that we have changed the file. But as it notes, we must add it to our list of files we want to update. We do this by:

```
git add .
```

The "." signifies adding all the changes you made.

##### (6) Commit.

When we **`commit`** a file, we tell Git that we're about to make our change final. This gives Git a chance to record any changes made. We also need to provide a message saying what changed so that other programmers can understand what we did.

```
git commit -m "added arms"
```

##### (7) Push

We are now ready to `push` our modified code to Github's servers. We do this by:

```
git push origin master
```

You can now go to your repository on GitHub and see the changes you made.

##### (8) Pull Request

Now that our repo is up to date we will need to ask the owner of the orignal repo to accept our changes with a **`pull request`**.

A **pull request** is completed by clicking the small green button on the repo page  
![Imgur](http://i.imgur.com/BqY9CA9.png) 


### Guided Practice ("We do")

Before everyone gets started on this project, we will divide up in pairs and assign a Potato Head body part to each pair.

The teacher will match each grouping of students with a body part:

* Arms
* Ears
* Eyes
* Mouth
* Nose
* Eyebrows



### Independent practice ("You do")
Build the Potato Head.

1. Fork the instructor's repo.
2. Clone your new repo in cloud.
3. Add your Potato body part to `potatohead.html`.

In the Cloud 9 terminal, type the following commands:

1. git status
2. git add .
3. git commit -m "Commit message"
4. git push origin master (or whatever initial branch is, typically master)

After **pushing** your code, send a **pull request** to the owner of the **repo**.

### Exit Ticket

Give the Exit Ticket.

### Closing

Accept all of the **pull requests** and show off everyone's work on the board by plugging the potatohead.html URL into www.rawgit.com

### Homework

[Link to Homework](homework/)

Remind students when homework is due and how it will be collected.

## After Class

* Review the Exit Tickets.
* Prepare for next lesson / hand off to next volunteer in rotation.
