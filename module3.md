---
layout: page
title: Module 3
permalink: /module3/
---

# Day 4. Version Control and Cluster Computing
Version control is the lab notebook of the digital world: it's what professionals use to keep track of what they've done and to collaborate with other people. Every large software development project relies on it, and most programmers, data scientists and bioinformaticians use it for their everyday work. It is important to note that version control is not just for software: research projects, books, courses (like this one), papers, small data sets, and anything that changes over time or needs to be shared can and should be stored in a version control system.

Today’s morning sessions with introduce [Git](https://git-scm.com/), currently the most popular version control system. We will learn how to perform common operations with Git that you’ll do every day. We will also cover the popular social code-hosting platforms [GitHub](https://github.com/) and [BitBucket](https://bitbucket.org/).

Afternoon sessions will introduce cluster computing. Computer clusters typically aim to provide much faster processing speed, larger storage capacity, wider availability of resources and often unique computing capabilities. We will first introduce cluster computing concepts in general and how to use the [UM Flux cluster](http://arc-ts.umich.edu/flux/) in particular. Topics to be covered include a review of common parallel programming models and basic use of Flux; dependent and array scheduling; troubleshooting and analysis using checkjob, qstat, and other PBS tools. We will then discuss various practical strategies for dividing and parallelizing workflows and utilizing checkpoints.

<br>

### Schedule:

| Session | Time             | Topics                                                   | 
| :-----: |:----------------:| :--------------------------------------------------------| 
| I       | 9:00-10:15 AM    | **Version Control with Git**                             | 
|         | 10:15-10:30 AM   | Coffee Break                                             | 
| II      | 10:30-12:00 AM   | **Collaborating with GitHub & BitBucket**                | 
|         | 12:00-1:00 PM    | Lunch                                                    | 
| III     | 1:00-2:15 PM     | **Concepts in Cluster Computing**                        | 
|         | 2:15-2:30 PM     | Coffee Break                                             | 
| IV      | 2:30-4:00 PM     | **Parallelization Strategies and Workflow Management**   | 


<br>

### Instructors:
Barry Grant (BG)  
Ryan Mills (RM)  
Ken Weiss (KW)

### Assistants:
Chris Scheller (CS)

<br>

### Topics:

### I)   Version Control with Git [1:15 hr]  BG ([Slides](../class-material/slides_day3-1_git.pdf))
- What is VCS and Git?,  (10-15 mins)
- Motivation: Why use Git?
 - Project snapshot history with rollbacks, Track changes from others, Sharing and updating mechanism, Keeping work organized and available.
- Obtaining and configuring Git
- Using Git
 - Important Git commands (init, add, commit, status, log, diff, blame, checkout)
 - Git workflows (the HEAD pointer, undo, stash, clean)
 - Git branches
- GUIs

—- Coffee Break [15 mins] —

### II)   Collaborating with GitHub [1:30 hr]  BG ([Slides](../class-material/slides_day3-2_github.pdf)) ([Tutoral](https://github.com/bioboot/demo2-github))
- Online Remote Repositories GitHub & Bitbucket
 - Paradigm shift in software development (permissions and open development)
 - The GitHub steam-train and StackOverflow 
- Working and Collaborating with Remotes (git clone, pull, push)
- Online GitHub & Bitbucket exploration
- Forking an online repository
- Pull requests
- Additional features (Issues, Dashboard, github-pages, hooks, CI etc.)
 


—- Lunch Break [1 hr] —

### III)   Concepts in Cluster Computing [1.15 hr]  KW  
- Connecting to FLUX
- Why cluster computing? 
- Cluster job submission
- Cluster job management
- etc. (nohup & tumx?)

—- Coffee Break [15 mins] —

### IV)   Parallelization Strategies & Workflow Management [1.30 hr] RM
- [Using Clusters for Exploring Large Data Datasets](../class-material/day4-clusters.html)

—- End/Wrap-Up —

<br>

### Reference material
[Git Reference Commands and Glossary](../class-material/git-reference.html)  
<!--- files dont exist yet...
[Slides-4.1]()
[Slides-4.2]()
-->


<br>

### Links / Further Reading

[Comprehensive 'Git Pro' book](http://git-scm.com/book/en/v2/)  
[GitHub home page](https://github.com/)  
[GitHub help pages](https://help.github.com/)  
[Excellent Bitbucket git tutorals](https://www.atlassian.com/git/)   
[List of good resources for learning git and GitHub](https://help.github.com/articles/good-resources-for-learning-git-and-github/)  

[Flux cluster homepage](http://arc-ts.umich.edu/flux/)  
[Flux training workshops](http://arc-ts.umich.edu/training-workshops/)  

  

