Plate Paper
==========

Collaborative journal paper on peridynamic plates

Made public after publication see DOI:[10.1016/j.ijsolstr.2014.09.003](http://dx.doi.org/10.1016/j.ijsolstr.2014.09.003)


To clone:

````
git clone https://github.com/johntfoster/PlatePaper.git
````

After making changes in your local repository, commit then _locally_ with:

````
git commit -a -m "A Commit Message"
````

the `-a` option adds all currently tracked files to the local commit.  The `-m` 
option allows for an inline commit message, if omitted it will open up an
editor for you to include a longer commit message.

When your ready to push your changes to the github repo:

````
git push origin master
````

`origin` is the default name given to the remote github repository when the
initial clone is done.  `master` is the default branch.

To sync your local repo with `origin master` on github:

````
git pull
````

### Creating a LaTeX diff from the repository

```
latexdiff-vc -c ld.cfg -r fcceb64d6 --math-markup=0 PlatePaper.tex
````

where `207e8e9` should be replaced with the correct `git` commit.
