**Project Name**:
GNOME Clocks
([Gitlab Repository](https://gitlab.gnome.org/GNOME/gnome-clocks/))
---

**Evaluating Person or Team**:
- Jessica Wong
- Daniel Mallia
- Boubacar Diallo

---


### License

1. What is the project's license?
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
<br>

The project's license is the GNU General Public License Version 2, June 1991.

---

### Code Base


1. What is the primary programming language in the project? <br>
[Vala](https://wiki.gnome.org/Projects/Vala) is the main programming language.

1. What is the development environment? For example, is it Gnu C++ on Linux? Are there instructions for how to download, build, and install? <br>

As GNOME Clocks is primarily written in Vala, which gets compiled down to C (instead of machine language) and then compiled for local use with a C compiler, contributing would involve a couple of ingredients. These are the: 
- Vala compiler 
- C compiler (default gcc)
- pkg-config (tool to pass library information to the C compiler)
- C standard library (typically glibc)
- Glib2 library 

There do not appear to be any clear instructions for how to download, build and install. 
<br>

1. Does the project depend on external additional software modules such as database,  graphics, web development, or other libraries? <br>
Yes, the project does have some software module dependencies, a list of which can be found [here](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/meson.build). The project's [HACKME](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/HACKME) document provides a [link](http://www.valadoc.org/) to documentation for these libraries.
<br>

1. Is the code easy to understand? Browse some source code files and make a judgment based on your random sample. <br>


<br>

1. Is this a big project? If you can, find out about how many lines of code are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>
fff
<br>


1. Does the repository have tests?
<br>
fff
<br>

---

### Code and Design Documentation
1. Is there clear documentation in the code itself?
<br>
Comments are sparse in the [src](https://gitlab.gnome.org/GNOME/gnome-clocks/-/tree/master/src) directory, but used in necessity to point out FIXME's, TODO's, translator notes, and steps in complicated functions. 
Some files are much more well documented than others, such as [alarm.vala](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/src/alarm.vala). Also, the functions and variables in the code are very clear and purposeful, helping hint at what is going on.
<br>

2. Is there documentation about the design?
<br>
fff
<br>


---


### Activity Level


1. How many commits have been made in the past week?
<br>
**23** commits have been made within the last week.
<br>

1. When was the most recent commit?
<br>
The most recent commit was authored 10 minutes ago. It was [Update Turkish translation](https://gitlab.gnome.org/GNOME/gnome-clocks/-/commit/e6465df5bd55006a2c3b75445eae8b725edcf74b).
<br>

1. How many issues are currently open?
<br>
There are **28** open issues as of now.
<br>

1. How long do issues stay open? 
Take the five most recently closed issues and look at when each was first reported. Compute the number of days that each was open and take the average.
<br>
    - 291 + 406 + 270 + 80 + 0
    - Average number of days an issue stays open based off of the last 5 closed issues: 209.4 days
    
<br>

1. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.
<br>
Yes, there is active discussion on the issues.
<br>

1. Are issues tagged as easy, hard, for beginners, etc.?
<br>
The issues are not tagged on their difficulty level. The tags I see are: Out of Scope, Feature, Crash, Bug, Translation, Needs Information, or Not Actionable. The "Out of Scope" and "Not Actionable" issues could be argued as high difficulty, however, there aren't issues that are tagged as easy or for beginners.
<br>

1. How many issues were closed in the past six months?
<br>
Within the last six months, **33** issues were closed.
<br>

1. Is there information about how many people are maintaining the project?
<br>
There are **2** maintainers for this project.
<br>

1. How many contributors has the project had in the past six months?
<br>
fff
<br>

1. How many open pull requests are there?
<br>
There is currently **one** open merge request.
<br>

1. Do pull requests remain un-answered for a long time? Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.
<br>
fff
<br>

1. Is there active discussion on the pull requests? Use the same method as you did for the issues.
<br>
fff
<br>

1. How many pull requests were opened within the past six months?
<br>
There were **** pull requests opened within the past six months.
<br>

1. When was the last  pull request  merged?
<br>
The last pull request was merged **one** hour ago.
<br>
---
### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it? Look through it and see if it is clear and thorough.
<br>
fff
<br>

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that violate it?
<br>
fff
<br>

1. Do the maintainers respond helpfully to questions in issues? Are responses generally constructive? Read the issue conversations.
<br>
fff
<br>

1. Are people friendly in the issues, discussion forum, and chat?
<br>
fff
<br>

1. Do maintainers thank people for their contributions?
<br>
fff
<br>

### Summary
Do you think  this is a project to which it would be possible to contribute in the
course of a semester?

Honestly speaking, 