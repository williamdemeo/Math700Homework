# Math700: Homework Files

This is the main repository for homework problems and solutions.

If you have questions, comments, or suggestions, please open a [New Issue].

Main course web page: https://github.com/williamdemeo/LinearAlgebra


## How To Submit Homework

If you are new to Git, please try the [15 Git minute tutorial][].  Also,
[git--the simple guide][] and the [GitHub help pages][] are excellent.  For
detailed comprehensive documentation see http://git-scm.com/doc.

1.  First, you should tell me your GitHub username so I can add you as a
    collaborator on the Math700Homework project.  

    (Actually, this isn't absolutely necessary, and you could still contribute
    using [forks][] and [pull requests][] if you weren't a collaborator, but since the
    class is small, I think it will be easier if all students taking the class
    for credit are collaborators.) 

2.  Next, you should [install Git][] on your computer.

3.  Once I add you as a collaborator, you should [clone][] the Math700Homework
    repository to your computer's hard drive.  How you do this may depend on 
	your operating system. In Linux I invoke the following at the command line
	
	    cd ~/git
		git clone git@github.com:williamdemeo/Math700Homework.git

4.  Make some changes to the files in the repository.  For example, you might
    edit the file called Homework01.tex.
	
5.  [Commit][] your changes to your local version of the repository.  I do:

        git add Homework01.tex
		git commit -m "added a sentence to make the proof clearer"
		
    (In quotes is your comment explaining, if possible, *why* the
    changes were made.)
	
6.  [Push][] your changes to the remote GitHub repository:

        git push origin master

    If you get errors, please let me know!
	

## Tips

+ If you've set up Git properly on your machine, you don't have to enter your
GitHub password when you push.

+ If you're a fan of Emacs, you will love an emacs package called [magit][], which
enables you to commit and push without leaving the emacs editor. (If you have
any trouble setting this up, please ask me about it.)  
	
+ [This page][] on recording changes to the repository is extremely informative.
There is a lot of information on that page.  If you're new to version
controlling, don't be scared, we'll only need the very basics.
	
+ Optimally, your commit comments should indicate *why* changes were made, 
and not *what* was changed. Git keeps a perfect record of what was changed, so
comments mentioning this are somewhat redundant (although they can cometimes be
helpful).  Instead, try to give some justification of the changes.
This is often hard to do in just a few lines and without spending too
long thinking about each commit, so don't worry too much; just
keep it in the back of your mind.
		
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
[15 Git minute tutorial]: http://try.github.io/levels/1/challenges/1
[This page]: IEProps/tex/
[magit]: http://magit.github.io/
