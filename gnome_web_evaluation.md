**GNOME Web (Epiphany)**:


---

**Evaluating Person or Team**: Team 1


---


### License

1. What is the project's license?
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
<br>
License was in a file titled "COPYING". The license used is the GNU Public License v3.0.
---

### Code Base


1. What is the primary programming language in the project?
<br>
C and Javascript

2. What is the development environment? For example, is it Gnu C++ on Linux?
Are there instructions for how to download, build, and install?
Downloaded, and compiled using their JHBuild program. Makes use of GNU Toolchain programs and python runtime. 
Additionally there are instructions for building from the source in the README.md file. Utilizes the Meson build system.
<br>

3. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries?
<br>
Python runtime environment.

4. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample.
<br>
No. They really don't comment or document their code.

5. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/).
<br>
156,000 lines of code as of now.


6. Does the repository have tests?
<br>
Yes.


---

### Code and Design Documentation
1. Is there clear documentation in the code itself?
<br>
There is an absence of comment in their C files (both the source and the header files). Their style is also horrifying (personally).

2. Is there documentation about the design?
<br>
For their code style and project structure, yes. Looking further there appears to be more on design, like the "Modern WebKit Process Architecture." Upon second look, alot of design info is in the README.md file. Front end guidelines, their manifesto (and its components), etc.


---


### Activity Level


1. How many commits have been made in the past week?
<br>
**41 Commits** (or pipelines, according to Gitlab).

2. When was the most recent commit?
<br>
Last commit was fifteen hours ago.

3. How many issues are currently open?
<br>
182

4. How long do issues stay open?
Take the five most recently closed issues and look at when each was first reported.
Compute the number of days that each was open and take the average.
<br>
At least 19 days

5. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.
<br>
Sort of? Some have conversations dotting along the months on a single issue, others are closed with zero comments.

6. Are issues tagged as easy, hard, for beginners, etc.?
<br>
Only four issues are tagged for "newcomers" yet they were all opened at least a year ago.
No tags regarding difficulty of issue.

7. How many issues were closed in the past six months?
<br>
286 (manually counted. Can't do date searches on Gitlab and the Github has no issue tracker).

8. Is there information about how many people are maintaining the project?
<br>
Among the Gitlab, Github, and project website, I was unable to find any definitive list of maintainers. I've seen two that are active in comments, issues, commits, and so forth.

9. How many contributors has the project had in the past six months?
<br>
OpenHub's graph puts active contributors for the last 6 months at 26 contributors.


10. How many open pull requests are there?
<br>
Open merge requests on Gitlab total at eight. There’s no open pull requests on their Github.

11. Do pull requests remain un-answered for a long time?
Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.
<br>
No, they're merged almost within the same day. Largest deviation witnessed is perhaps a whole day, but nothing more.

12. Is there active discussion on the pull requests?
Use the same method as you did for the issues.
<br>
Not really, no.

13. How many pull requests were opened within the past six months?
<br>
Github says one. There’s eight on the Gitlab, advanced search doesn't provide for searching by date created.


14. When was the last pull request merged?
<br>
3 days ago.

---
### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough.
<br>
It exists. Major sections are **Software versions**, **Web Content Bugs**, and **Crashes**.

2. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it?
<br>
Can't be found. The community seems quite civil and even self-reflective somehow.

3. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive?
Read the issue conversations.
<br>
Yes.  Responses are generally constructive, insightful. 

4. Are people friendly in the issues, discussion forum, and chat?
<br>
In the issues, yes. There is an IRC as well, but no other asynchronous discussion channels have been found.

5. Do maintainers thank people for their contributions?
<br>
No. Some merge requests get merged without any discussion.

### Summary
Do you think  this is a project to which it would be possible to contribute in the
course of a semester?
While this is an open source project that can be contributed to, the lack of documentation greatly hinders the ability to efficiently read and understand the code as one needs to really read the code thoroughly to begin understanding what is happening. The upside to this project is that issues get dealt with in a timely manner. 
