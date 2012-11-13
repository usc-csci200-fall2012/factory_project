Since many of us are new to git and GitHub, a number of issues come up during the submission process. I will be presenting these issues in this page. Most of these points require actions from most but not necessarily all teams. Regardless, you need to make sure your repository satisfies any requirement listed here.

### Wiki Home Page
A number of teams did not edit their wiki's home page (`Home.md`) making it a bit harder on the graders to see their document. Please edit your wiki's home page to either be your document or a list of links showing the flow of the document.

***

### Relative links in wiki
A number of teams have been using non-relative links when linking wiki pages to each other. This makes grading hard since it always points to the _current_ version of the wiki not the one that should be graded. To fix this, please use relative links for all your URLs. A relative wiki link would look like **&#91;link to this wiki's home page&#93;&#40;wiki/Home.md&#41;** which would produce: [link to this wiki's home page](wiki/Home.md).

***

### Issue Milestones
For grading purposes, each team must add the following [milestones](https://github.com/blog/831-issues-2-0-the-next-generation) to their issue tracker:

+ Grading - Factory Design
+ Grading - Factory Skeleton v. 0
+ Grading - Factory v. 1
+ Grading - Factory v. 2

These will be used by graders to post grading issues related to each submission.

***

### Submission Tagging
In order to make retrieving your official submissions easier, you will tag your deliverables with the following names:

+ `design`
+ `v0.0`
+ `v1.0`
+ `v2.0`

Feel free to add more tags to mark specific milestones in your project, e.g. `v0.3` or `v1.6.35`. However, the above mentioned tags are project-specific tags that you **must** have.

Tag signing and annotation is optional and **do not** use lightweight tags.

A very clear discussion on tagging could be found in the [Pro Git](http://git-scm.com/book) book [Chapter 2.6](http://git-scm.com/book/en/Git-Basics-Tagging)

***

### Grading Environment
Submissions will be graded on [`aludra.usc.edu`](http://www.usc.edu/its/unix/servers/scf.html) using [Java 1.6](http://www-scf.usc.edu/~csci200/java6_setup.html) via the terminal.

***

### Issue Tracker
Teams are to use the issue tracker to keep track of all their:
  + Bugs
  + Enhancements
  + Requested Features
  + Tasks, etc.

Each closed issue must have:
  + The SHA of the commit resolving or partially resolving the issue
  + The number of this issue mentioned in the commit message closing it using the [proper syntax](https://github.com/blog/831-issues-2-0-the-next-generation).

Teams not using the issue tracker effectively will get panelized.