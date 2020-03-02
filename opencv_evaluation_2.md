**Project Name**: Open Computer Vision Library (opencv)


---

**Evaluating Person**: Steven Santana


---

### Installation
1. Report on whether you were successful installing the project on your local machine.
   I was able to follow the instructions listed on their documentation/wiki page (there are alot of different kinds, for different platforms too). Installing/building the core libraries required an IDE with a compiler (say Microsoft Visual Studio), CMake, and TortoiseGit. I only chose this option because it felt like the most "proper" way to install this as a potential contributor. There are alot of steps and interfaces that may be confusing or intimidating to first timers. Even with the instructions (so much optional details). The simplest part was adding the environment variable to the system path.


### License

1. What is the project's license?
   In most repositories there will be a file named LICENSE or something similar in
   the root level of the repository. This is the one to examine. There may be
   different licenses on specific files, but the project will have a main license.
   <br>
   3-Clause BSD License   
 
---

### Code Base


1. What is the primary programming language in the project?
   <br>
   C++

1. What is the development environment? For example, is it Gnu C++ on Linux?
   Are there instructions for how to download, build, and install?
   <br>
   * "An IDE of your choice, or just a CC++ compiler that will actually make binary files."
   * CMake
   * Git
   

1. Does the project depend on external additional software modules such as
   database,  graphics, web development, or other libraries?
   <br>
   * For Python Interface: python libraries, Numpy.
   * Intel Threading Building Blocks (TBB) for better multicore performance.
   * Eigen (a C++ template library for linear algebra).
   * Doxygen
   
   

1. Is the code easy to understand? Browse some source code files and make
   a judgment based on your random sample.
   <br>
   
   Sort of. Well organized.
   

1. Is this a big project? If you can, find out about how many lines of code
   are in it, perhaps on [OpenHub](https://www.openhub.net/).
   <br>
   1.93 Million Lines of code


1. Does the repository have tests?
   <br>
   Yes.


---

### Code and Design Documentation
1. Is there clear documentation in the code itself?
   <br>
	In comments? No.

1. Is there documentation about the design?
   <br>
   In the documents, yes.


---


### Activity Level


1. How many commits have been made in the past week?
   <br>
   60

1. When was the most recent commit?
   <br>
	As of today (02/28/20), two hours ago (about 3pm EST).

1. How many issues are currently open?
   <br>
   1702 issues are currently open.

1. How long do issues stay open?
   Take the five most recently closed issues and look at when each was first reported.
   Compute the number of days that each was open and take the average.
   <br>
   Out of a sample of five, it appears issues are open for around a day, max.

1. Is there active discussion on the issues?
   Read the conversations from some open and some closed issues.
   <br>
   For some issues, discussion is active. For many more there is little or no discussion.

1. Are issues tagged as easy, hard, for beginners, etc.?
   <br>
   The "good first issue" tag exists. And there are tags for speculated effort level, each denoted with the amount of time it may take. For example, "effort:(infinity sign)" states to not attempt this issue on ones own. 
   There are 6 "good first issue" issues open. There are, combined, 19 "effort" issues open.

1. How many issues were closed in the past six months?
   <br>
	642 issues have been closed since August 28th, 2019.

1. Is there information about how many people are maintaining the project?
   <br>
   There is not. Upon trying to find a (definitive) method to determine who is a maintainer, it appears such knowledge is up
   to a given user to display as they choose. 

1. How many contributors has the project had in the past six months?
   <br>
   According to the Insights tab on the Github repo, 23 contributors.


1. How many open pull requests are there?
   <br>
   60 open pull requests.

1. Do pull requests remain un-answered for a long time?
   Look at the closed pull requests to see how long they stayed open.
   Take the five most recently closed ones and look at when each was first reported.
   Compute the number of days that each was open and take the average.
   <br>

   Once again, about a day if not less.
   
1. Is there active discussion on the pull requests?
   Use the same method as you did for the issues.
   <br>
   There is at least one comment in any given closed pull requests, but for most there is exactly one. Unsure if I can
   safely say that is activity as there is not much back and forth discussion.

1. How many pull requests were opened within the past six months?
   <br>
   As of 02/28/20, 637 pull requests have been opened.


1. When was the last  pull request  merged?
   <br>
	The last pull request was merged two hours ago.

---
### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
   Look through it and see if it is clear and thorough.
   <br>
   It exists and merely links to a wiki page titled as "How to contribute". Its very clear and not particularly
   verbose despite the topics it covers. Theres even a link to a "writing documentation for OpenCV" page.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
   violate it?
   <br>
   There is no document as such, not in the repo nor on any of their related websites. Additionally their slack link is dead so I will have to assume its informal.

1. Do the maintainers respond helpfully to questions in issues?
   Are responses generally constructive?
   Read the issue conversations.
   <br>
   As I haven't detected any (explicit) maintainers through viewing comments on issues and prs, I'll say that the
   approving contributers on issues and prs are constructive in their input when they choose to voice their concerns.

1. Are people friendly in the issues, discussion forum, and chat?
   <br>
   In the issues, yes. In their "Forum" (more like a reddit style online discussion forum) there is surprisingly little discussion for the many questions present, so I can't judge that.

1. Do maintainers thank people for their contributions?
   <br>
   Doesn't appear to be that way.

### Summary
Do you think  this is a project to which it would be possible to contribute in the
course of a semester?

I am attracted by the heavy use of C++ and topic but I'm afraid the topic and work itself is quite out of my league, even as a senior. Where the community acts like one they seem helpful and the documentation is decent enough to help someone jump into it, however its alot to handle, despite how much they've divided their code into modules (also a good look for them).