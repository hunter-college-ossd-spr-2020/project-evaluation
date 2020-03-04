**Project Name**:  
Libreoffice


---

**Evaluating Person or Team**:  
Keisuke Suzuki


---


### License

1. What is the project's license?  
**GNU General Public License v3**
---

### Code Base

1. What is the primary programming language in the project?  
**C++**

1. What is the development environment? For example, is it Gnu C++ on Linux? Are
   there instructions for how to download, build, and install?  
    * **Building Environments**
        * Windows:
	    Runtime: Windows 7
            Build: Cygwin + Visual Studio 2017 version 15.7
        * macOS:
            Runtime: 10.10
            Build: 10.14.4 + Xcode 11.3
        * Linux:
            Runtime: RHEL 7 or CentOS 7
            Build: either GCC 7.0.0; or Clang 5.0.2 with libstdc++ 7.3.0
        * iOS (only for LibreOfficeKit):
            Runtime: 11.4 (only support for newer i devices == 64 bit)
            Build: Xcode 9.3 and iPhone SDK 11.4
        * Android:
            Build: NDK r19c and SDK 22.6.2.  
    * **There are a detailed [documentation](https://api.libreoffice.org/) and a [
video Instruction](http://www.youtube.com/watch?v=2gIqOOajdYQ&hd=1).**


1. Does the project depend on external additional software modules such as
   database, graphics, web development, or other libraries?  
**Yes.**

1. Is the code easy to understand? Browse some source code files and make a
   judgment based on your random sample.  
**Yes, as far as I checked they are indented well with rich comments.**

1. Is this a big project? If you can, find out about how many lines of code are
   in it.  
**It is a massive project. It has 9.51M lines of code, according to
   [OpenHub](https://www.openhub.net/).**

1. Does the repository have tests?  
**Yes, they are in *root*/test**.

---


### Code and Design Documentation
1. Is there clear documentation in the code itself?  
**Yes**

1. Is there documentation about the design?  
**Yes, they can be referred from [
this page](https://wiki.documentfoundation.org/Design).**

---


### Activity Level


1. How many commits have been made in the past week?  
**1085**

1. When was the most recent commit?  
**Mar 1, 2020**

1. How many issues are currently open?  
**None**

1. How long do issues stay open?  
**No issues are recorded in Github's read only repository**

1. Is there active discussion on the issues?  
**No**

1. Are issues tagged as easy, hard, for beginners, etc.?  
**No**

1. How many issues were closed in the past six months?  
**None**

1. Is there information about how many people are maintaining the project?  
**Could not find the information**

1. How many contributors has the project had in the past six months?  
**Could not figure out how to count contributors other than github.**

1. How many open pull requests are there?  
**11**

1. Do pull requests remain un-answered for a long time?
 Look at the closed pull requests to see how long they stayed open.
 Take the five most recently closed ones and look at when each was first reported.
 Compute the number of days that each was open and take the average.  
**(49 + 43 + 0 + 0 + 0)/2 = 46, so 46 days** 

1. Is there active discussion on the pull requests?  
**No, because there is no issues on github.**

1. How many pull requests were opened within the past six months?  
**None**

1. When was the last  pull request  merged?  
**None**


---

### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is
   it? Look through it and see if it is clear and thorough.  
**No**

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it?  
**No**

1. Do the maintainers respond helpfully to questions in issues? Are responses
   generally constructive? Read the issue conversations.  
**They ask people to contribute form their [
Gerrit repository](https://gerrit.libreoffice.org/q/status:open)**

1. Are people friendly in the issues, discussion forum, and chat?  
**Same as above.**

1. Do maintainers thank people for their contributions?  
**Yes, even though they do not accept pull requests from github, they usually
say thank you to those attempted.**

### Build Log
1. I cloned the repository, and followed the instruction for installing 
   dependencies.
   ```bash
   cd && sudo apt-get install git ccache junit4 gstreamer1.0-libav libkrb5-dev 
   nasm graphviz libpython3-dev
   ```

1. Ran the the bootstrap script:
   ```bash
   ./autogen.sh
   ```
   However, it kept saying about missing packages. I had to install:   
   - `libfontconfig1-dev`
   - `gperf`
   - `JDK`
   -  `doxygen` from source, because the precompiled one was not working well on
       my machine, and what I needed: 
       - `flex`
       - `bison` 
   - `libxslt1-dev`
   - `xsltproc`
   - `libxml2-utils`
   - `libxext-dev`
   - `gtk-3.0-dev`
   - `libxrandr-dev`
   - `libgstreamer1.0-dev`
   - `libgstreamer-plugins-base1.0-dev`
   - `ant`

1. Finally, I can run  ```make```  
And it took over four hours to be built...

1. After all, I ran
    ```
    ./instdir/program/soffice --writer
    ```
    Fortunately, the word like application showed up on my screen.  

### Summary

Do you think  this is a project to which it would be possible to contribute in the
course of a semester?  
**I think it is possible to contribute to this project, but as a beginner, 
contributing to projects that use github as their main hub. Besides that, 
fewer dependencies would be better. **