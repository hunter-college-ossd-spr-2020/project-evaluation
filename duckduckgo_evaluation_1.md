**Project Name**:
[DuckDuckGo Privacy Essentials](https://github.com/duckduckgo/duckduckgo-privacy-extension)
---

**Evaluating Person or Team**:
- Boubacar Diallo

---


### License

1. What is the project's license?
In most repositories there will be a file named LICENSE or something similar in
the root level of the repository. This is the one to examine. There may be
different licenses on specific files, but the project will have a main license. <br> 
The project's [license](https://github.com/duckduckgo/duckduckgo-privacy-extension/blob/develop/LICENSE) is the **Apache License, Version 2.0**. The DuckDuckGo logos and marks used in the project are actually licensed separately under the **CCBY-NC-ND 4.0**.

---

### Code Base


1. What is the primary programming language in the project? <br> 
**Javascript** is the main programming language, with a sprinkle of **CSS** also used.

1. What is the development environment? For example, is it Gnu C++ on Linux? Are there instructions for how to download, build, and install? <br> 
The `CONTRIBUTING` document contains [a section](https://github.com/duckduckgo/duckduckgo-privacy-extension/blob/develop/CONTRIBUTING.md#development) with basic instructions on building, developing, and testing. The project uses a [**Node.js**](https://nodejs.org/) development environment, and scripts for these actions are run using [npm](https://www.npmjs.com/). 

1. Does the project depend on external additional software modules such as database, graphics, web development, or other libraries? <br> 
The dependencies of the project are listed in the [package.json](https://github.com/duckduckgo/duckduckgo-privacy-extension/blob/develop/package.json#L61) file. Notable development specific library dependencies are [Selenium](https://www.selenium.dev/) and [Grunt](https://gruntjs.com/).

1. Is the code easy to understand? Browse some source code files and make a judgment based on your random sample. <br>
The code is written in clean, modern Javascript, which might have some hangups for beginners in the language (ex. arrow functions). The variable and function names give hints as to what is going on, and it's not too difficult to follow the general flow of each function.

1. Is this a big project? If you can, find out about how many lines of code are in it, perhaps on [OpenHub](https://www.openhub.net/). <br> A DuckDuckGo project exists on OpenHub, but it is not related to this extension (the project on the site is written mostly in Perl). If I had to guess about the size of the project based on the [code frequency tab](https://github.com/duckduckgo/duckduckgo-privacy-extension/graphs/code-frequency) on Github it could be in the range of 200k - 300k lines of code. There are only 21 contributors, so it is a **medium to large size project**.

1. Does the repository have tests?<br> **Yes**.There are 3 separate test directories, for unit tests, integration tests, and selenium webdriver tests. Since it is a heavily browser focused project it seems testing is very important to the success and maintenance of the app.
---

### Code and Design Documentation
1. Is there clear documentation in the code itself?<br> Some directories are much more documented than others, such as the [shared/js/background](https://github.com/duckduckgo/duckduckgo-privacy-extension/tree/develop/shared/js/background) directory, which contains background scripts. However, files that don't contain many comments seem fairly self-documenting, and comments are used across the project's codebase to clear up any possible confusion or specifications.

1. Is there documentation about the design?<br> The `CONTRIBUTING` document contains a short [section](https://github.com/duckduckgo/duckduckgo-privacy-extension/blob/develop/CONTRIBUTING.md#development-flow) explaining the connection between folder structures and functionality. Besides this, there is not much mention of code design.

---


### Activity Level


1. How many commits have been made in the past week?<br>
There haven't been any commits on the main `develop` branch since early December, however checking the [Network Graph](https://github.com/duckduckgo/duckduckgo-privacy-extension/network) there have been 10 commits by one contributor on their personal feature branch in the last week.

1. When was the most recent commit?<br> The most recent commit on the main branch was almost **3 months ago**.


1. How many issues are currently open?<br> **67 issues**

1. How long do issues stay open? 
Take the five most recently closed issues and look at when each was first reported. Compute the number of days that each was open and take the average.<br> 
0, 0, 114, 98, 2:  **42.8** days on average. 


1. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.<br> **Partially**, a small amount of the issues have discussions, but those that do are helpful and constructive.

1. Are issues tagged as easy, hard, for beginners, etc.?<br>
There is a [`good-first-issue`](https://github.com/duckduckgo/duckduckgo-privacy-extension/labels/good%20first%20issue) tag, but no issues or pull requests have been made for it yet.

1. How many issues were closed in the past six months?<br>
Within the last six months, **5** issues were closed.

1. Is there information about how many people are maintaining the project?<br> Maintainers aren't specifically mentioned anywhere, but the top several contributors seem to be the people accepting/merging pull requests and closing issues.

1. How many contributors has the project had in the past six months?<br> There have been about **4** contributors in the past 6 months.

1. How many open pull requests are there?<br> **21** currently open pull requests.

1. Do pull requests remain un-answered for a long time? Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.<br> Except for one pull request that was open for a little less than 3 weeks, most of the recent pull requests are closed within a day or so. A lot of these pull requests are usually also from the same few contributors. Pull requests that get changes requested seem to be open for 1-3 weeks.

1. Is there active discussion on the pull requests? Use the same method as you did for the issues.<br> About a third of the pull requests have discussions on them.

1. How many pull requests were opened within the past six months?<br>
There were **17** pull requests opened within the past six months.

1. When was the last  pull request  merged?<br>
The [last pull request](https://github.com/duckduckgo/duckduckgo-privacy-extension/pull/421) was merged on December 12, 2019.

---

### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it? Look through it and see if it is clear and thorough.<br> **Yes**, there is a straightforward `CONTRIBUTING` document with instructions on reporting bugs, feature requests, building, developing, and testing. However, it only covers the essentials and does not seem very thorough.


1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that violate it?<br> **No** CODE OF CONDUCT document exists.

1. Do the maintainers respond helpfully to questions in issues? Are responses generally constructive? Read the issue conversations.<br> Maintainers thank people for reporting issues and bugs, and responses are overall very constructive.

1. Are people friendly in the issues, discussion forum, and chat?<br> There is no mention of a discussion forum or chat, but discussions in the issues are friendly and helpful.

1. Do maintainers thank people for their contributions?<br> **Yes**, maintainers usually thank people for both making pull requests and reporting bugs in the issues.

---

### Installation Process

The installation process seemed very straightforward at first, but I ran into a few bugs. Since I had prior experience with all the weirdness of npm, it only took about 40 minutes to figure out all the issues and get the project to build. I already had the first prerequisite, Node.js, installed, so I went straight to building.

First of all, the [build instructions](https://github.com/duckduckgo/duckduckgo-privacy-extension/blob/develop/CONTRIBUTING.md#testing-locally) didn't mention that `npm install` **must** to be run in the directory of the project before any other scripts. Maybe they assumed everyone would know that going in? A multitude of errors cascaded down after running the install command. From experience, I decided to mostly ignore them and try running the scripts first to see which dependencies specifically were actually causing problems. There was an issue with Grunt, and I had to download the [CLI](https://gruntjs.com/getting-started#installing-the-cli) globally using `npm install -g grunt-cli`. After the fact, I realized this is what was meant when Grunt.js was included in the list of prerequisites in the extension's build instructions. It wasn't very clear at first, since grunt is also an npm package on its own that is already listed in the package.json. After this, the script to build the project (`npm run dev-firefox`) partially ran, but stopped due to errors. A package that was supposed to be installed was mentioned as a suggestion in the output, so I tried installing it alone using `npm install grunt-sass`. The same issues came up from the previous install, and so it was time to face the music. I first searched issues in the project's repo to see if anyone else had problems installing, but only [one non-related issue](https://github.com/duckduckgo/duckduckgo-privacy-extension/issues/265) came up where someone trying to solve the issue mentioned the same problem with installing. However, the bug in the original issue was fixed and the comment on installation was completely ignored. After generally searching I found a solution on Github: delete the package-lock.json file and install again. This changed a version value for grunt-sass in package.json from 2.0.0 to ^2.0.0 ([allowing latest minor or patch version](https://michaelsoolee.com/npm-package-tilde-caret/)), and finally the script to build the project files worked. The final installation step was to actually load the built extention in the browser, which had a Mozilla guide and Google Chrome guide respectively linked for each browser in the installation instructions.

All in all, the usual run arounds and npm quirks came up when trying to install. The instructions were very straughtforward but basic, and missing some steps beginners could have struggled with.

### Summary
Do you think this is a project to which it would be possible to contribute in the course of a semester?

The `README` specifically mentions that the project is solely looking for bug reports or bug fixes at the moment, and no feature pull requests will be accepted. It would be possible to use the project and report bugs as a contribution during the semester, but bug fixes may require a higher level of knowledge in web development, browser functionality, and Javascript. Most of the accepted pull requests are from the same several contributors, who have a pretty deep knowledge of the project. Though it isn't necessarily not beginner friendly, the project doesn't exactly lend itself toward a beginner contributor.
