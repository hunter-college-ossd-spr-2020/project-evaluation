**Project Name**:
TEAMMATES
([Gitlab Repository](https://github.com/TEAMMATES/teammates))
---

**Evaluating Person or Team**:
- Jessica Wong
---


### License

1. What is the project's license?
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.

- The project's license is the GNU General Public License Version 2, June 1991.

---

### Code Base


1. What is the primary programming language in the project? <br>[**Java**](https://en.wikipedia.org/wiki/Java_(programming_language)) is the main programming language.

1. What is the development environment? For example, is it Gnu C++ on Linux? Are there instructions for how to download, build, and install? <br>As GNOME Clocks is primarily written in Vala, which gets compiled down to C (instead of machine language) and then compiled for local use with a C compiler, contributing would involve a couple of ingredients. These are the: Vala compiler, C compiler (default gcc), pkg-config (tool to pass library information to the C compiler), C standard library (typically glibc), and Glib2 library. There do not appear to be any clear instructions for how to download, build and install.

1. Does the project depend on external additional software modules such as database,  graphics, web development, or other libraries? <br>Yes, the project does have some software module dependencies, a list of which can be found [here](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/meson.build). The project's [HACKME](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/HACKME) document provides a [link](http://www.valadoc.org/) to documentation for these libraries. The HACKME also points to an [article](https://blogs.gnome.org/tvb/2013/05/29/composite-templates-lands-in-vala/), which gives some indication of how a developer will work with UI templates.

1. Is the code easy to understand? Browse some source code files and make a judgment based on your random sample. <br>
Vala is a C-like language (perhaps unsurprising given that it compiles down to C) and is therefore fairly straightforward to read; thus the same can be said for the GNOME Clocks code. There are higher-level OOP concepts at play and this does detract from some clear readability, but as with any codebase, understanding comes with sufficient time.

1. Is this a big project? If you can, find out about how many lines of code are in it, perhaps on [OpenHub](https://www.openhub.net/). <br>According to OpenHub, GNOME Clocks consists of approximately six thousand lines of code and would therefore be considered a small project in the world of software development by that metric. While the project has over 250 contributors in total, work on it appears to be largely limited to a few developers. 

1. Does the repository have tests?<br>While there are a couple of tests for the UI, there do not appear to be any unit tests for the balance of the code.
---

### Code and Design Documentation
1. Is there clear documentation in the code itself?<br>Comments are sparse in the [src](https://gitlab.gnome.org/GNOME/gnome-clocks/-/tree/master/src) directory, but used in necessity to point out FIXME's, TODO's, translator notes, and steps in complicated functions. 
Some files are much more well documented than others, such as [alarm.vala](https://gitlab.gnome.org/GNOME/gnome-clocks/-/blob/master/src/alarm.vala). Also, the functions and variables in the code are very clear and purposeful, helping hint at what is going on.

1. Is there documentation about the design?<br>There is a [design page](https://wiki.gnome.org/Design/Apps/Clock#Objectives) that mentions the objectives of the app, however the rest of the page mainly contains mockups and wireframes of the app's frontend design. The GitLab repo doesn't seem to contain anything mentioning the code/directory structure or functional components of the project either.

---


### Activity Level


1. How many commits have been made in the past week?<br><b>2</b> commits have been made within the last week. 

1. When was the most recent commit?<br>The most recent commit was authored 2 hours ago. 

1. How many issues are currently open?<br>There are <b>243</b> open issues as of now.

1. How long do issues stay open? 
Take the five most recently closed issues and look at when each was first reported. Compute the number of days that each was open and take the average.<br>0 + 0 + 4 + 6 + 0<br>Average number of days an issue stays open based off of the last 5 closed issues: <b>2</b> days

1. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.<br>Yes, there is active discussion on a majority of the issues.

1. Are issues tagged as easy, hard, for beginners, etc.?<br>I see that there are issues tagged as **FirstTimers**, however none are tagged easy or hard. However, I do see some issues tagged as **Low**, **Medium**, and **High**, referring to the level of impact the issue will have on the project. The other issues are tagged for what the issue is, like **Feature** or **Bug**. 

1. How many issues were closed in the past six months?<br>Within the last six months, <b>xx</b> issues were closed.

1. Is there information about how many people are maintaining the project?<br>There are **xx** maintainers for this project.

1. How many contributors has the project had in the past six months?<br>**xx** authors staged <b>xx</b> commits within the last 10 months.

1. How many open pull requests are there?<br>There is currently <b>one</b> open merge request.

1. Do pull requests remain un-answered for a long time? Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.<br>0 + 0 + 3 + 10 + 0 <br>The average number of days pull requests stay open is <b>3</b> days.

1. Is there active discussion on the pull requests? Use the same method as you did for the issues.<br>Yes, there is active discussion on the pull requests.

1. How many pull requests were opened within the past six months?<br>There were **14** pull requests opened within the past six months.

1. When was the last  pull request merged?<br>The last pull request was merged <b>six</b> hours ago.

---

### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it? Look through it and see if it is clear and thorough.<br>Yes, I found a CONTRIBUTING document [here](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md). This document is easy to read and understand because they have organized sections within the document directing us to various topics of interest for contributing. For instance, they have a ***Getting started*** section, a ***How can I contribute?*** section, and a ***Contributor orientation guide***.

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that violate it?<br>Yes, I found a CODE OF CONDUCT document [here](https://github.com/TEAMMATES/teammates/blob/master/.github/CODE_OF_CONDUCT.md). It mentions that the community fosters a welcoming environment for everyone. Project maintainers in this project have the right to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that violate the code of conduct. The document also states that ***"All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances"***.

1. Do the maintainers respond helpfully to questions in issues? Are responses generally constructive? Read the issue conversations.<br>Based off of the issue conversations, the community seems very understanding and knowledgable. I saw that a couple of people are really thankful for some issues being opened by the community. Also, if somebody is confused, then they would ask for clarification. If there is an unaddressed problem, then the community would explain what the issue is in great detail.

1. Are people friendly in the issues, discussion forum, and chat?<br>Yes, the people thank others for their contributions. If somebody asks a question, then others in the community are willing to answer without hesitation. If somebody is confused, then they would say "Can you please elaborate...?".

1. Do maintainers thank people for their contributions?<br>
Yes, they do! As previously mentioned, the maintainers thanked the community when opening up very useful issues.

---

### Installation Process Reflection

This is my installation process.

---

### Summary
Do you think this is a project to which it would be possible to contribute in the course of a semester?

This project is extremely active with a great community. 