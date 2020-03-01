**Project Name**: 
TEAMMATES
([Github Repository](https://github.com/TEAMMATES/teammates))


---

**Evaluating Person or Team**: 
Daniel Mallia

---


### License

1. What is the project's license?
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license.
<br> The TEAMMATES license is the GNU General Public License Version 2, 1991. 
---

### Code Base


1. What is the primary programming language in the project?
<br> Java is the the leading programming language in the project: Github reports that 76.4% of the project consists of Java code. 

1. What is the development environment? For example, is it Gnu C++ on Linux?
Are there instructions for how to download, build, and install?
<br> The development environment for TEAMMATES consists of Git, the Java Development Kit, the Gradle Build Tool, and Python 2.7 for any kind of work on the project, and Node.js and Angular CLI (only recommended)  There is a nice guide for setting up this "TEAMMATES development environment" [here](https://github.com/TEAMMATES/teammates/blob/master/docs/setting-up.md).

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries?
<br> The project depends on the external software  listed in the package.json file - npm (Node Package Manager) refers to this file and using *npm install* will install these.

1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample.
<br> The code in TEAMMATES does seem to be very clean and easy to read. [This](https://github.com/TEAMMATES/teammates/blob/master/src/main/java/teammates/logic/core/InstructorsLogic.java) is a very nice example.

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/).
<br> Yes, TEAMMATES does appear to be a project of considerable size. According to [OpenHub's Page](https://www.openhub.net/p/teammates-on-github/analyses/latest/languages_summary), TEAMMATES consists of almost 140K lines of code. 


1. Does the repository have tests?
<br> Yes, there is an entire folder dedicated to testing code. 


---

### Code and Design Documentation
1. Is there clear documentation in the code itself?
<br> The code is well documented: it is immediately apparent from visual inspection and is confirmed by OpenHub's statistic that there just over 22K lines of comments in the repository. 


1. Is there documentation about the design?
<br> Yes, there is very thoughtful and comprehensive documentation about the design [here](https://github.com/TEAMMATES/teammates/blob/master/docs/design.md).


---


### Activity Level


1. How many commits have been made in the past week?
<br> As of Saturday, February 29th, there have been 6 commits to the master branch over the last week.

1. When was the most recent commit?
<br> The most recent commit was Friday, February 28th, and, for reference, there were 4 commits made on Friday.

1. How many issues are currently open?
<br> As of Saturday, February 29th, there are 240 issues currently open.

1. How long do issues stay open?
Take the five most recently closed issues and look at when each was first reported.
Compute the number of days that each was open and take the average.
<br> Trying to calculate how long issues stay open on this project suffers from a classic statistics problem: outliers. Looking at the 5 most recent issues, as of Saturday, February 29th, these were open for 1 day, less than a day, less than a day, 4 days, and 6 days. While these suggest an average of (1+0+0+4+6) / 5 =  2.2 days (with some rounding to whole/no days), these may not be very representative issues because two of the issues lasted less than a couple of hours and were quick open and shut issues due to a contributor determination / improper issue. Looking beyond the 5 recent commits, it looks like this number should be raised to somewhere in the 4-6 days range, depending on the complexity of the issue, but some issues are nonetheless resolved quickly.

1. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.
<br> There is a moderate amount of conversation on issues, particularly on the more serious and technical matters. 

1. Are issues tagged as easy, hard, for beginners, etc.?
<br> Yes, there is tagging as of difficulty, as with for "FirstTimers" or "Contributors".

1. How many issues were closed in the past six months?
<br> 48 issues were closed in the past six months.


1. Is there information about how many people are maintaining the project?
<br> There is a [page](https://teammatesv4.appspot.com/about.jsp) which lists the different groups of contributors to the project, beginning with the core team (though the term *maintainers* is not used).

1. How many contributors has the project had in the past six months?
<br> There have been 4 contributors to master in the past six months.


1. How many open pull requests are there?
<br> There are 38 open pull requests.

1. Do pull requests remain un-answered for a long time?
Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.
<br> Pull requests generally do not remain un-answered for a long time but may take as little as 1 day to resolve (or even 0 days if the pull request is made in error... as with one of these cases) or up to 11 days, with much discussion and changes along the way. Overall, with some rounding to no/whole days, 1 + 1 + 0 + 7 + 11 / 5 = 4 days on average to close a pull request. 

1. Is there active discussion on the pull requests?
Use the same method as you did for the issues.
<br> Yes, there is certainly active discussion on the pull requests and this seems to frequently include helpful screenshots.

1. How many pull requests were opened within the past six months?
<br> 77 pull requests were opened within the last six months.


1. When was the last  pull request  merged?
<br> The last pull request was merged on Friday, February 28th, 2020. 

---
### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough.
<br> Yes there is a very comprehensive, readable and helpful "[Contributor Orientation Guide](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md)".

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violte it?
<br> Yes, there is a [code of conduct](https://github.com/TEAMMATES/teammates/blob/master/.github/CODE_OF_CONDUCT.md) and it does state the following: "All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances." It also states the responsibility of maintainers to adhere to and enforce this code.

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive?
Read the issue conversations.
<br> Maintainers respond helpfully and constructively to questions and discussions in some issues: see [here](https://github.com/TEAMMATES/teammates/issues/9940) for a nice example. However, maintainers and contributors do seem to have to remind many potential contributors to follow issue guidelines and proper setup/installation procedures, deflect suggestions of questionable value (see [here](https://github.com/TEAMMATES/teammates/issues/9540) for an example), and are frequently bombarded with requests from people who want to contribute but don't always seem to follow up. This does appear to limit the responses of maintainers - perhaps due to burnout. 

1. Are people friendly in the issues, discussion forum, and chat?
<br> Per the previous response, the tone of the community is generally polite and friendly, but can also be *firm* while remaining professional. Overall it does appear to be a friendly project community.

1. Do maintainers thank people for their contributions?
<br> Maintainers do seem to be openly appreciative of contributions but often the expression of this is from a quick "LGTM" or "Looks Good To Me". See [here](https://github.com/TEAMMATES/teammates/pull/9941) for an example.

### Summary
Do you think  this is a project to which it would be possible to contribute in the
course of a semester?

Teammates does appear to be a project that a student could contribute to in the course of a semester, **provided they are already familiar with Java or web development**. The continuing activity of the project, installation and contribution guides, abundance of documentation, labeling of issues by difficulty, and moderate level of discussion on Github, seem to together offer ample opportunities for contributions. That said, installation alone may prove to be a headache: see below for more.

### Personal Installation Experience:
I followed the [installation guide](https://github.com/TEAMMATES/teammates/blob/master/docs/setting-up.md) and while I had no trouble following the steps for setting up the development environment, I ran into trouble immediately after that stage... The first set of instructions pertains to just downloading the files and is very helpful for a contributor who is new to Git. Step 2 concerns language support. Python is not an issue as Python 2.7 ships with Ubuntu and MacOS; instead the hardest part here is downloading JDK (Java Development Kit) 1.8, as Oracle requires an account to be made before downloading and, for some reason, "Company Name" is a required field?! I did not download the front-end tools as I would not work on that aspect of the project given the choice and the same applies to my working through step 3, where the balance of the steps went down without issue. After these few short steps, you are ready to begin development. There is a [development](https://github.com/TEAMMATES/teammates/blob/master/docs/development.md) document on where to go next. Here I found instructions on starting the back-end dev server and attempted to do so as a final test of the installation process and was unfortunately greeted with a wall of errors related to Google Cloud tools. While there is a [troubleshooting guide](https://github.com/TEAMMATES/teammates/blob/master/docs/troubleshooting-guide.md) for developers, and the guide does suggest going back to the PATH variable for the Google Cloud SDK mentioned in the installation guide, it assumes you installed the SDK and this only points to a serious flaw in the installation guide. The Google Cloud SDK is only mentioned in passing in the installation guide, with a note that you can *"choose"* to set a different path for the SDK if you want, but it does not even clearly state that you must install another SDK. **Why the guide would specify something as rudimentary as installing Python but neglect to specify installing an SDK, without which you are left with a nausea-inducing flood of errors warning of illegal actions, is beyond me.**