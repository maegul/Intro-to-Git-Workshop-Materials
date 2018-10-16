
<style type="text/css">

	h1 {
		color: #D6865D;
		border-bottom: 2px solid !important; 
		margin-top: 45px !important;
	}

	h2 {
		color: #c14678;
		border-bottom: 2px solid !important;
		margin-top: 35px !important;
	}

	#highlight {
		font-weight: bold;
		color: #358CA6;
	}

</style>

<iframe style="margin: auto" src="https://slides.com/errollloyd/gitintro/embed" width="100%" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>

[TOC]

# Introduction

## Workshop Ethos at ResPlat


* Technically empower researchers
	* Programming
	* Open Source
	* Practical

* Connect researchers to form a community
	* **openness**, 
	* **friendliness**, 
	* **helpfulness**
	* [Facebook Group](https://www.facebook.com/groups/522053638172827/)
	* [My (Errol) Twitter](https://twitter.com/maegul)


## Why Use Git



* ⚡️Powerful / Professional / State of the Art

* ⚙️ But ... way you use it is quite flexible
	* Can be used at many levels of complexity or simplicity
	* *No one completely masters git - Everyone is using it at the level that suits them*
	* **Trick is to just start using it to get it into your workflow**

* 🏛 Version Control
	* Keeps track of the changes you make to text files.

* 🌏 GitHub
	* Open Publications and Hosting Online


## What is Git



1. **Version Control** (better than backup)
1. **Distributed Version Control**


<iframe style="margin: auto; height: 80vh" src="https://slides.com/errollloyd/gitintro/embed#/3" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

---

<br>

---

<br>
<br>
<br>
<br>

# Workshop Structure

<div style="display: flex">
	
<img style="margin: auto; width: 100%;" src="./SpiralPath.png">

</div>

<br>

* Four concepts / skills
* Repeated Four Times:
	1. Basic Concept
	1. Explanation
	1. Demonstration
	1. Exercise for you

# How Git Works Pt I


<iframe style="margin: auto; height: 80vh;" src="https://slides.com/errollloyd/gitintro/embed#/5" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>

# How Git Works Pt II

## 📖 Dear Diary / Captains Log	


* How your Diary or Log is made:
	1. Git 
		<span id='highlight'> Tracks the Changes You've Made </span>
	1. You're in control of 
		<span id='highlight'> when a log is made </span>, and 
		<span id='highlight'>what is written about the work</span>


<iframe style="margin: auto; height: 80vh;" src="https://slides.com/errollloyd/gitintro/embed#/7" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>



## 🕰 Time Travel



* <span id='highlight'>Review</span> 
	any part of the 
	<span id='highlight'>history</span> 
	of your work
* <span id='highlight'>Alter or Undo</span> 
	some of your past work


<iframe style="margin: auto; height: 80vh;" src="https://slides.com/errollloyd/gitintro/embed#/8" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>




## 🌜🌛 Parallel Universes


* Keep <span id="highlight">independent versions</span> of your project
* But, can <span id="highlight">split and re-merged</span> whenever you like
* Perfect for <span id='highlight'>experimental</span> work and <span id='highlight'>collaboration</span>


<iframe style="margin: auto; height: 80vh;" src="https://slides.com/errollloyd/gitintro/embed#/9" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>



## 🛰 Space Station 

* Free & Online cloud storage
* Your version control <span id='highlight'>shared and published</span> online
* GitHub as well as a number of popular alternatives (BitBucket, GitLab, etc)


<iframe style="margin: auto; height: 80vh;" src="https://slides.com/errollloyd/gitintro/embed#/10" width="100%" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<br>


# Demonstration

## 📖 Dear Diary / Captains Log

### Key Concepts

Concept                                       | Description
-                                             | -
Work Normally                                 | Git doesn't interfere with your work or how you work; you use git only once you wish to add your recent work to your history
Git Pays Attention                            | Git is like an annoying historian that notices every little change you've made to your files since the last time you logged your work to your history.  These recorded changes are what git analyses and git will record them automatically in your history.


### Actions

Action                                        | Description \ Purpose
-                                             | -
Make Folder                                   | Version control happens within folders
Initialise Git                                | Git starts tracking your files only once you start it
Do work                                       | Your work on files as normal, git doesn't interfere
Log Work or Version                           | When ready, add your recent work, describe it, and add it to your history

### Vocabulary

Word                                                      | Description
-                                                         | -
<span id='highlight'>Repository</span>                    | Repo for short.  A folder in which you have initialised git to keep track of all the changes you make in it.
<span id='highlight'>Diff (difference)</span>             | The differences between the current files and what they were like in the last recorded version in the history of the Repository.
<span id='highlight'>Hunk</span>                          | A set of lines close to each other that have been changed
<span id='highlight'>Commit (verb)</span>                 | The action of adding a set of changes as a new version to the history of your repo
<span id='highlight'>History</span>                       | All the versions that have been committed for a single repository
<span id='highlight'>Commit (noun)</span>                 | A single set of changes that were all committed at once.  When you commit a set of changes, they all get recorded as a single "version", or point in the history of your repository.  These sets of changes, or points in history, are often referred to as *commits*.  *Commits* have metadata attached to them, including the person who made the commit, the time it was done, and a unique identifying number called a SHA
SHA                                                       | Stands for Secure Hash Algorithm.  A unique number given to every commit made with git.


## 🕰 Time Travel

### Key Concepts

Concept                                                   | Description
-                                                         | -
Each commit is a point in time                            | When you commit a set of changes, the state of the files at that time get recorded as a single commit.  On top of this, each commit is aware of which commit came before, and which commit comes after.
A commit is a set of diffs                                | The changes made in each commit can be easily viewed as a set of diffs or hunks for each file, which show which lines of your files were deleted and which lines were added or modified.  These diffs highlight the work you actually did.
Git modifies your files                                   | As all of your history is stored in the database of your git repo, git happily modifies your files to reflect the particular part of your history that wish to view.  This is safe, as the current version of your files are stored in the database and are unaffected.



### Actions

Action                                                    | Description \ Purpose
-                                                         | -
Make Commit                                               | Normal commit of changes to your files
Review your History                                       | Look at the diffs for each commit
Undo a particular commit by "reverting" it                | A reversion undoes the effect of a particular commit

### Vocabulary

Word                                                      | Description
-                                                         | -
<span id='highlight'>Revert</span>                        | The action of telling git to undo or cancel out a previously logged commit.  Git automatically generates a new commit that has the effect of cancelling out the previous commit.  Your files will now look as though the previous commit never occurred.


## 🌜🌛 Parallel Universes

### Key Concepts

Concept                                                   | Description
-                                                         | -
Splitting History                                         | Git allows you to take a particular point in your history, ie a particular commit, and create multiple independent histories that all start from that commit or point.  They will all share that point in your history, and all those before, in common, but are free to have their own unique commits afterwards.  These are called *branches*.
Merging History                                           | Independent Histories or *branches* that were previously split can be merged back together by taking the unique commits of one branch and inserting them into another branch.
Feature or Experimental Branches                          | The typical use for branches is for implementing experimental or uncertain features into your project, where your files are in a good state, and you don't know exactly how you're going to implement the new feature.  Doing so in an isolated branch allows for stability, and gives you the option to merge the feature into your main project when it is working appropriately.
Git Modifies your files                                   | As mentioned under Time Travel above, git happily modifies your files so that they reflect the part of your history that you are trying to view.  The same applies to viewing branches.  When you are viewing a particular branch, your files are changed to reflect the history of that particular branch.



### Actions

Action                                                    | Description \ Purpose
-                                                         | -
Make a Branch                                             | Creates new independent history that splits from the most recent commit (of the current branch)
Do work or make changes                                   | Branches behave in the same way as you've seen so far where you commit changes to your history as normal.
Compare Branches                                          | In the same way that the work of a particular commit can be seen as a set of diffs that show what changes were made for that commit, you can see the diffs between two branches, that show the changes that would have to be made to make one branch look like another.  This allows you to compare branches and see what is relative valuable in any branch.
Merge Branch                                              | If the work done in a particular branch is desirable in another branch, you can merge that work into this branch.  All of the commits will be added and the branch you've merged into will appear as though the work was done there too.


### Vocabulary

Word                                                      | Description
-                                                         | -
<span id='highlight'>Branch</span>                        | An independent history of commits that has been split off from your main history at a particular point or commit.
<span id='highlight'>Master Branch</span>                 | Each branch has a name.  Your main history has a branch name too, because it is also technically a branch.  By default, it's name is *master*.


## 🛰 Space Station

### Key Concepts

Concept                                                   | Description
-                                                         | -
GitHub stores you repositories on the cloud               | The main thing that GitHub does is allow you to store your whole project, including all of the history recorded for your repository, online in the cloud.  Importantly, GitHub runs git as well, so you can access and interact with your cloud repository in much the same way you do with the repository on your own computer.
GitHub is one of a number of alternatives                 | GitHub is popular, but a number of popular alternatives exist that value privacy more than GitHub.  These include GitLab and Bitbucket.
Keep Repo and Cloud up to date by *Pushing* and *Pulling* | You keep the repository on your computer and the one on the cloud (GitHub) up to date with each other by *Pushing* your repository up to the cloud and by *pulling* the cloud down to your computer.


### Actions

Action                                                    | Description \ Purpose
-                                                         | -
Make GitHub account                                       | Free and easy to do at github.com
Add your account to your git app                          | Your git app will log into GitHub for you everytime you want to push or pull, so it needs to know your log in details
Push your repository                                      | Push your repository up to GitHub and log in to check that your repository is now available there, including all of the history.

### Vocabulary

Word                               | Description
-                                  | -
<span id='highlight'>Remote</span> | Anywhere that you store you repository other than its main and original location, is a remote for git.  This includes GitHub and its alternatives, as well as any other computer that you *push* and *pull* repositories with.
<span id='highlight'>Local</span>  | Describes the repository that is on your computer, the one you're currently using.
<span id='highlight'>Push</span>   | This updates a remote repository with all of the latest commits from the local repository.
<span id='highlight'>Pull<span>    | This updates the local repository with all of the latest commits from the remote repository.
<span id='highlight'>Fetch<span>    | Related to Pull.  This gets all the relevant information and data from the remote about what needs to updated in the local repo, but does not actually perform the update.  It just checks to see what's needed to give you the option of performing it or not.


# Challenges

## 📖 Dear Diary / Captains Log

* Make a New Repository
* Open your text editor
* Get sample file  - 
	* copy and paste from below
	* See “Sample File” heading below
* Save it as a .py file to get commenting shortcuts
	* Cmd/Ctrl + / (usual shortcut)
* Put your file in your repository
* Add each function separately and commit separately
	* Add appropriate commit messages


### 👹 Extension

* Make some new changes to the file (anything is fine) that have not yet been committed.   
	* Using icons around and near the line numbers of the code, can you work out how to commit specific lines only?

* If you have multiple files, each with their own changes, can you work out how to commit only the changes of a single file.
	* Add another file, by copying the second sample below, to test this out.


#### Sample File

These are basic python scripts.  **You don't need to worry about coding in python though!!**  

The hashes `#` at the beginning of every line comment those lines.  To have the same effect as typing, simply uncomment those lines, with either the hot-key in your text editor or by simply deleting.

```python
# def addition(a, b):

# 	summation = a + b

# 	return summation


# def subtraction(a, b):

# 	difference = a - b

# 	return difference


# def division(a, b):

# 	quotient = a / b

# 	return quotient

# def multiplication(a, b):

# 	product = a * b

# 	return product

```

#### Second Sample File

```python
# def bad_addition(a, b):

# 	summation = a + b + 0.002

# 	return summation


# def bad_subtraction(a, b):

# 	difference = a - b + 7

# 	return difference


# def bad_division(a, b):

# 	quotient = (a+13) / b

# 	return quotient


# def bad_multiplication(a, b):

# 	product = a * b + 12

# 	return product

```

## 🕰 Time Travel

* Revert two of the functions you've committed (*they don't have to be the most recent ones*)
	* Check your file to see that the relevant change has taken place


### 👹 Extension

* Delete on of your files and then bring it back
* Use your history to look at the changes made in each commit.  
	* Do you feel like you understand the pluses (`+`) and minuses (`-`) in the diff?
	* Can you work out what the `@@ [numbers] @@` symbols at the top of the diff mean?
* Can you revert a reversion?


## 🌜🌛 Parallel Universes

* Make sure you have two branches.
	* In one branch, add another function
	* In the other branch, change a function that already exists
	* Merge both of these new branches into your master branch

* Make a branch from your master
	* In the new branch, change a line (any line) to something different.
	* In the master branch, change the same line to something different again (and different from what you did in the new branch)
	* Now try to merge them
	* 👹 <span style="color: #C82023">See if you can work out how to resolve the situation you've created</span>
		* Can you understand why the problem exists given what you did to create it and what you did in the first part of this challenge?


## 🛰 Space Station

* Get GitHub account (github.com)
* Add it to your desktop app
* Push your repository to GitHub
* Let me clone it (paste the link to it in google doc)


### 👹 Extension

* Clone the repository for these materials to your own machine
* Fork the repository to your GitHub account
	* Edit the file to make it better and make a pull request




# Resources

## Download Links

[GitHub Desktop App](https://desktop.github.com/)


Text Editors:

* [VS Code](https://code.visualstudio.com)
* [Atom](https://atom.io)
* [Sublime Text](https://www.sublimetext.com)



## Additional Tools and Services

[Get Private Repositories on GitHub as student or researcher](https://education.github.com)

* Click the `Join GitHub Education` button

---

* Alternatives to GitHub that offer privacy immediately
	* [BitBucket](https://bitbucket.org/product)
	* [GitLab](https://about.gitlab.com)
	* [GitLab at University Melbourne](https://gitlab.unimelb.edu.au/users/sign_in)

---

**Command Line Git**

[General Installation Instructions](https://resbaz.github.io/intro-git-workshop/)
[Git for Windows](https://gitforwindows.org/)



**Other Applications** (Generally more powerful than GitHub Desktop App)

[SourceTree](https://www.sourcetreeapp.com)
[GitKraken](https://www.gitkraken.com)
[Sublime Merge](https://www.sublimemerge.com/#light)



## Other Educational Materials on Git

### Recommended Documentation and Materials

* [Software Carpentry Course Materials on using git](https://swcarpentry.github.io/git-novice/)

* [Official Guide Book](https://git-scm.com/book/en/v2)


### Nice Tutorials

* [git - the simple guide](http://rogerdudler.github.io/git-guide/)

* [learn enough git to be dangerous](https://www.learnenough.com/git-tutorial#sec-viewing_the_diff)

* [Interactive Tutorial App](https://github.com/jlord/git-it-electron#what-to-install)

* [Interactive Tutorial Web Page](https://learngitbranching.js.org)

### More thorough guides

* [interactive cheat sheet](http://www.ndpsoftware.com/git-cheatsheet.html)

* [git magic](http://www-cs-students.stanford.edu/%7Eblynn/gitmagic/)

* [A visual git reference](http://marklodato.github.io/visual-git-guide/index-en.html)

* [conversational git](http://blog.anvard.org/conversational-git/)
