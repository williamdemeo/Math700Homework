# Math700: Homework Files

This is the main repository for homework problems and solutions.

If you have questions, comments, or suggestions, please open a [New Issue].

Main course web page: https://github.com/williamdemeo/LinearAlgebra


## How To Typeset Homework Solutions

When it is your week to submit the "official" homework solutions, you must use
the [LaTeX document preparation system](http://www.latex-project.org/).  If you
don't already know how to use LaTeX, there is
[plenty of online documentation](#latex-resources) to help you get started, but
please *feel free to ask me if you need help!*  At the bottom of this page are
some [links to LaTeX resources](#latex-resources). 


## How To Submit Homework Solutions

**Overview**

We will use Git and GitHub to manage the homework files for this class.
Here is a rough overview of what you will do when it is your turn to submit
official solutions (more details below):

First you will download our Math700Homework Git repository to your hard drive.
Then you will type your solutions in the tex/Homework*.tex file corresponding to the
assignment for which you are responsible. You will commit your changes to
your local version of our repository.  Finally, on the assignment due date, you
will sync your version of our repository with the online version.

If you are new to Git, please try the [15 minute Git tutorial][].  Also,
[git--the simple guide][] and the [GitHub help pages][] are excellent.  For
detailed comprehensive documentation see http://git-scm.com/doc.

**Details**

1.  First, tell me your GitHub username so I can add you as a
    collaborator on the Math700Homework project.  

2.  Next, [install Git][] on your computer.  

3.  If you are using a Mac or Linux, [upload a public ssh key][]
    to your GitHub account. (If you are using [GitHub for Windows][] 
	you can skip this step.)

3.  Once I add you as a collaborator, you can [clone][] the Math700Homework
    repository to your computer's hard drive.  How you do this may depend on 
	your operating system. 
	+ **Linux.** Invoke the following at the command line:
	
	        mkdir -p ~/git
		    cd ~/git
	        git clone git@github.com:williamdemeo/Math700Homework.git

	  the same commands should work on a Mac in a terminal window.
	  See also the [first Tip](#tips) below.
	+ **Windows.** I have never used the [GitHub for Windows][] app, so I don't
      know how to clone a repo in Windows.  However, according to
  	  [this help.github.com page][], it's easy. If you have problems,
      please consult http://windows.github.com/help.html
4.  Next, make some changes to the files in the repository.  For example, you might
    edit the file Homework01.tex in the Math700Homework/tex directory.
	
5.  [Commit][] your changes to your local version of the repository:

        git add Homework01.tex
		git commit -m "added a sentence to make the proof clearer"
		
    (In quotes is your comment explaining, if possible, *why* the
    changes were made.)
	
6.  On the [due date][] of the assignment for which you're responsible, [push][]
    your changes to the remote GitHub repository: 

        git push origin master

    If you get errors, please let me know!  
	
	As soon as you push your changes to GitHub, they will be viewable by
    everyone.  In order to give other students a chance to solve the problems on
    their own, please wait until the due date of the assignment to push your solutions.
	

## Git Tips
+ If you've set up Git and your GitHub account properly, you won't have to enter
your GitHub password every time you push changes to the repository. If you use a 
Mac or Linux, you should upload your public ssh key to your GitHub
account by following
[these instructions.](https://help.github.com/articles/generating-ssh-keys) In
Windows, this should work automatically if you use the
[native GitHub app](https://github-windows.s3.amazonaws.com/GitHubSetup.exe).

+ If you're a fan of Emacs, you might want to install the Emacs package called
[Magit][], which enables you to commit and push without leaving the Emacs
editor--very convenient!
	
+ [This page][] on recording changes to the repository is extremely informative.
There is a lot of information on that page.  If you're new to version
controlling, don't be scared, we'll only need the very basics.
	
+ Optimally, your commit comments should indicate *why* changes were made, 
and not *what* was changed. Git keeps a perfect record of what was changed, so
comments mentioning this are somewhat redundant (although they can sometimes be
helpful).  Instead, try to give some justification of the changes.
This is often hard to do in just a few lines and without spending too
long thinking about each commit, so don't worry too much; just
keep it in the back of your mind.

+ If you ever have any trouble using Git or GitHub, please let me know!
You can [email me](mailto:williamdemeo@gmail.com) or create a [new wiki page](https://github.com/williamdemeo/Math700Homework/wiki/_new) for discussing Git, or open a [new issue](https://github.com/williamdemeo/Math700Homework/issues/new).


## LaTeX Resources

+ **Downloading/Installing LaTeX**
  - [TeXLive](http://www.tug.org/texlive/) is for Linux users.
  - [MacTeX](http://www.tug.org/mactex/) is for Mac users.
  - [proTeXt](http://www.tug.org/protext/) is for Windows users.

+ **Using LaTeX**
  - [LaTeX project site](http://www.latex-project.org/)
  - [LaTeX WikiBook](https://en.wikibooks.org/wiki/LaTeX)
  - [The not-so-short guide to LaTeX](http://mirror.ctan.org/info/lshort/english/lshort.pdf)
  - [George Gratzer's short course](http://www.ctan.org/tex-archive/info/Math_into_LaTeX-4/)
  - [Introduction to Using TeX](http://www.math.harvard.edu/texman/texman.html) (Harvard)
  - [Some useful tips, esp. for Linux users](http://people.virginia.edu/~ll2bf/docs/quickref/latex.html) (Virginia)
  - [Video tutorials](http://www.spoken-tutorial.org/list_videos?view=1&foss=LaTeX&language=English)
	
+ **Finding Math Symbols**
  - [Comprehensive Symbol List](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf)
  - [Brief Symbol List](http://www.artofproblemsolving.com/Wiki/index.php/LaTeX:Symbols)
  - [Cheat Sheet (pdf)](http://ctan.math.washington.edu/tex-archive/info/latexcheat/latexcheat/latexsheet.pdf) [(html)](http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html)
  - [detexify][] If you can draw the symbol with your mouse, try [detexify][]!

Lots more links at: http://www.tug.org/begin.html



[due date]: https://github.com/williamdemeo/Math700Homework/wiki/Homework-Schedule
[upload a public ssh key]: https://help.github.com/articles/generating-ssh-keys
[New Issue]: https://github.com/williamdemeo/Math700Homework/issues
[Clone]: http://git-scm.com/book/en/Git-Basics-Getting-a-Git-Repository#Cloning-an-Existing-Repository
[clone]: http://git-scm.com/book/en/Git-Basics-Getting-a-Git-Repository#Cloning-an-Existing-Repository
[install Git]: https://help.github.com/articles/set-up-git
[Fork]: https://help.github.com/articles/fork-a-repo
[fork]: https://help.github.com/articles/fork-a-repo
[pull request]: https://help.github.com/articles/using-pull-requests
[forks]: https://help.github.com/articles/fork-a-repo
[pull requests]: https://help.github.com/articles/using-pull-requests
[Commit]: http://git-scm.com/book/en/Git-Basics-Recording-Changes-to-the-Repository#Committing-Your-Changes
[commit]: http://git-scm.com/book/en/Git-Basics-Recording-Changes-to-the-Repository#Committing-Your-Changes
[Push]: https://help.github.com/articles/create-a-repo#step-3-push-your-commit
[push]: https://help.github.com/articles/create-a-repo#step-3-push-your-commit
[15 minute tutorial]: http://try.github.io/levels/1/challenges/1
[A Beginner's Guide to LaTeX]: http://www.cs.princeton.edu/courses/archive/spr10/cos433/Latex/latex-guide.pdf
[LaTeX Guide]: http://en.wikibooks.org/wiki/LaTeX
[Git--the simple guide]: http://rogerdudler.github.io/git-guide/
[GitHub help pages]: https://help.github.com/
[15 minute Git tutorial]: http://try.github.io/levels/1/challenges/1
[This page]: http://git-scm.com/book/ch2-2.html
[Magit]: http://magit.github.io/
[detexify]: http://detexify.kirelabs.org/classify.html
[GitHub for Windows]: https://help.github.com/articles/set-up-git#platform-windows
[this help.github.com page]: https://help.github.com/articles/adding-repositories-with-github-for-windows
