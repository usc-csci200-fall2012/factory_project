## Introduction
[Git](http://git-scm.com/) is a distributed version control system developed by Linus Torvalds to be used for the Linux kernel development. It quickly grew to be one of the most widely used source code management systems.

In class, you have been introduced to [git](http://git-scm.com/), [GitHub](https://github.com/) and their use within the context of your project. This page will hold pointers to the introductory material and a listing of some git resources.

## A Basic Introduction to Git
+ [CS 200/201 - Presentation](http://www-scf.usc.edu/~alghanmi/csci200/git.pdf)
+ [CS 102 - Showing Your Code to The World](http://bit.ly/git_intro_by_alghanmi) (with detailed aludra setup instructions)

## Learning Git
As with almost all technologies, there are two main ways to learn things: a formal introduction (takes more time) or a quick tutorial to get you going fast. Depending on what you prefer, here are some good places to start:

### Formal Introduction to Git
1. If you are new to version control, or you want to get a lightweight overview before diving into the material, start with these set of short videos:
   + [What is Version Control?](http://git-scm.com/video/what-is-version-control)
   + [What is Git?](http://git-scm.com/video/what-is-git)
   + [Get Going with Git](http://git-scm.com/video/get-going)
   + [Quick Wins with Git](http://git-scm.com/video/quick-wins)
1. The [Pro Git](http://git-scm.com/book) book is a concise discussion of git, how and why it works. The book is available freely online and licensed under [CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).
    + For a basic intro to git, read chapters [1](http://git-scm.com/book/en/Getting-Started) and [2](http://git-scm.com/book/en/Git-Basics)
    + [Chapter 3](http://git-scm.com/book/en/Git-Branching) discusses branching which is an important aspect about git, however, it is not fundamental when you are just getting started.

### Tutorials
+ [GitHub's Try Git](http://try.github.com) is an interactive introduction which is also part of [Code School](http://www.codeschool.com/courses/try-git)
+ [Git Immersion](http://gitimmersion.com/)
+ [Learn.GitHub Video Tutorials](http://learn.github.com/p/intro.html)
+ [git - the simple guide by Roger Dudler](http://rogerdudler.github.com/git-guide/)

### Git Cheatsheets
+ [Tower Cheatsheet](http://www.git-tower.com/files/cheatsheet/Git_Cheat_Sheet_grey.pdf)
+ [Cheatsheet by Roger Dudler](http://rogerdudler.github.com/git-guide/files/git_cheat_sheet.pdf)
+ [git ready](http://gitready.com/) is a good place to find answers to very common questions

## GitHub Resources
+ [Git Setup](https://help.github.com/articles/set-up-git)
+ [GitHub Help Pages](https://help.github.com/)
+ [GitHub Stars & Notifications](https://github.com/blog/1204-notifications-stars)
+ [GitHub Email Notifications](https://github.com/blog/1214-notification-email-improvements)

### Markdown
+ [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/)
+ [Markdown Syntax Guide](http://daringfireball.net/projects/markdown/syntax)


## Special Git Topics
### git ignore files
+ [Sample Git Ignore File](https://github.com/usc-csci200-fall2012/factory_project/blob/master/sample.gitignore)
+ [The gitignore repository](https://github.com/github/gitignore)

### git tag
Tags are alphanumeric names given to specific commits. Essentially, bookmarking that commit for easy identification and use. The [submission notes](wiki/Submission-Notes) discuss the use of tags in your project-based submissions. Here are some references discussing tags:

+ [`git tag`](http://gitref.org/branching/#tag) from [Git Reference](http://gitref.org/)
+ Chapter [2.6 Git Basics - Tagging](http://git-scm.com/book/en/Git-Basics-Tagging) from the [Pro Git](http://git-scm.com/book) book.

### git log
The `git log` command is a very powerful command that helps you inspect the history of a repository. Here are some commonly used `git log` variations:

+ [Git Reference - Inspection & Comparison](http://gitref.org/inspect/)
+ [Bend logs to your will](http://gitready.com/advanced/2009/01/20/bend-logs-to-your-will.html)

## Using Git with IDEs
+ **Eclipse**: uses a plugin called egit. Here are some resources:
    + [Git with Eclipse (EGit) - Tutorial](http://www.vogella.com/articles/EGit/article.html) by Lars Vogel
+ **NetBeans**: has git built-in. Here is a guide on how to use git with NetBeans:
    + [NetBeans - Git User Guide](http://netbeans.org/kb/docs/ide/git.html)