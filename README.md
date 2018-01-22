# Here is a modification.

(the screencast videos are an ad libbed temporary solution until I get a chance to create proper scripted content.)

# The no nonsense GitHub Project. 
![alt tag](img/github_01.png) 
## A 1 hour no nonsense video tutorial series covering the basic usage of the world's most popular version control software! 

Are you a self-taught Web or Software developer looking to take your first steps into the world of collaborative development? Or a coding bootcamp student looking to work on your first group project? Or perhaps you have simply never used GIT before and could use a crash course on how to use this software? If any of these apply to you, you've come to the right place.

I'm Michael Desantis! A Full-Stack web developer and Teachers Assistant at the Coding Bootcamp at UT Austin. In this video course I will be introducing the basics of GIT and GitHub (and no, they're not the same thing). I am creating this repository and README here to use as a handy reference guide to accompany the video material.

In this tutorial, you can watch and take notes. Or you can build a GitHub Repository of your own and follow along, pausing the videos as necessary. This course is structured in such a way where all the exercises build on the material from the previous videos. I highly recommend building a repository and following along step-by-step.  

The goal of this project is to provide you, the end user, with a brief, concise, and fast-paced instructional on how to use GIT. By the end of these videos, you should have a basic yet functional grasp and understanding of how to implement GIT in your development and projects. Just click the YouTube icons to get started.


## Video 1 : Introduction to GIT and Version Control.
In this video, I'll be explaining the 5W's of GIT. What is Git? Why is it important? When should it be used? Who uses it? Where is it used? I'll also show you how to install and configure it for the first time. Don't worry, we'll go over how to use GIT in the next 7 videos.

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=s6qztDCpZUU) 

##### Helpful Links

1. https://git-scm.com/download  (download page)
2. https://git-scm.com/book/en/v2/Getting-Started-Installing-Git  (installation guide)
3. https://help.github.com/articles/set-up-git/ (configure your local computer to match your GitHub account)
4. https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/ (ssh credentials, because re-entering your password each time is time consuming)
5. https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/ (git documentation on setting up ssh)
6. https://services.github.com/kit/downloads/github-git-cheat-sheet.pdf  (github cheat sheet. Your most useful resource on this list)

##### New GIT commands used

```
1. git --version  (tells you what version you have installed)
2. git config --global user.name "Your Name"  (configure username)
3. git config --global user.email yourname@example.com  (configure email)
4. git config --list  (display user and email configurations)
```

## Video 2 : Building your first repository.
In this video, I'll guide you through building your first repository on your local computer. As well as how to connect it to GitHub. 

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=xSXi9sTl0EY) 

##### Helpful Links

1. https://help.github.com/articles/adding-a-file-to-a-repository-from-the-command-line/ (adding files from command line)
2. https://github.com/robbyrussell/oh-my-zsh  (oh-my-zsh plugin. It'll make your life a lot easier)

##### New GIT commands used

```
1. git init  (initialize git in local directory)
2. git remote add origin git@github.com:Username/Repository-Name  (connect your local repository to github)
3. git status  (see which files have been changed, and which ones you're adding)
4. git add fileName (track file, stage it for commit)
5. git checkout fileName  (discard file changes you don't want to add)
6. git commit -m "Your Message here" (commit your changes, attach a message, create save point)
7. git push origin master (send changes from your computer to GitHub)
8. git reset HEAD fileName  (un-stage a file to prevent commiting it)
```

## Video 3 : Your first collaborative exercise + basic workflow. 
In this video, I'll show you how to pull the latest changes from GitHub. How to fork and clone other peoples repositories. How to submit a pull request. And showing you a simple GitHub workflow. BONUS: learn how a gitignore file works! 

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=e_NZmxRb8wk) 


##### Helpful Links

1. https://help.github.com/articles/about-pull-requests/  (more detail on pull requests)
2. https://help.github.com/articles/fork-a-repo/ (don't worry if this seems a little advanced, we'll go into it in more detail in the upcoming videos)
3. https://help.github.com/articles/ignoring-files/ (using gitignore files in more depth)

##### New GIT commands used

```
1. touch .gitignore  (create .gitignore file)
2. git pull origin master  (pull latest changes from your GitHub repository)
3. git remote -v  (view remote connections)
```

## Video 4 : All about branching.
In this video, I'll show you what "branching" is. As well as how it works, why it's useful, and how to use it.

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=ob2gVudg-JI) 

##### Helpful Links

1. https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/  (branch management from github)
2. https://guides.github.com/introduction/flow/ (explanation on why branches are useful)
3. https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging  (branching in more depth)

##### New GIT commands used

```
1. git branch  (view all existing branches on your local repository)
2. git branch branchName (creates a new branch named branchName)
3. git checkout branchName  (switch from current branch onto a branch named branchName)
4. git checkout -b branchname (creates a new branch named branchName and switches to it, combination of above two commands)
5. git branch -d branchName  (delete a branch named branchName)
6. git merge branchName  (pull changes FROM branch named branchName INTO the branch you're currently on)
```

## Video 5 : Dealing with merge conflicts, remote repositories, and developing as a team. 
In this video, I'll show you some common issues encountered when developing as a team, how to resolve a merge conflicts, how to set up multiple remote repositories, and how to change the url connection to a remote repository. You'll also learn how to fetch changes, pull changes, and merge changes from other repositories sucessfully. 

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=fy1WsnJZOC4) 

##### Helpful Links

1. https://help.github.com/articles/fetching-a-remote/  (the fetch command in more detail)
2. https://help.github.com/articles/changing-a-remote-s-url/  (changing your remote url)

##### New GIT commands used

```
1. git remote add repoName https://github.com/Username/Repository-Name.git  (allows multiple remote repositories)
2. git fetch repoName branchName  (fetch changes from remote repo WITHOUT automatically merging them)
3. git pull repoName branchName  (get changes, pull and merge them onto local machine)
4. git remote set-url repoName git@github.com:Username/Repository-Name  (allows you to change the url for your GIT to GitHub connection)
5. git remote rm repoName  (remove a remote repository)
```

### At this point, you know enough GIT and GitHub to cover 95% of situations you're likely to encounter. I recommend building some familiarity with your new skills before advancing to the next 3 videos.

## Video 6 When things go wrong, and how to fix them.
In this video, I'll go over how to roll back to a previous commit in the event that something breaks. You'll also learn how to access previous versions of your code and the importance of why commit messages are so important.

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=uNY04FC2llk) 

##### Helpful Links

1. https://github.com/blog/2019-how-to-undo-almost-anything-with-git  (undo almost anything in git, detailed article)
2. http://stackoverflow.com/questions/4372435/how-can-i-rollback-a-github-repository-to-a-specific-commit  (community input on best practices when reverting a commit)
3. http://stackoverflow.com/questions/179123/how-to-modify-existing-unpushed-commits  (amending a commit message, also touches on git rebase)
4. http://stackoverflow.com/questions/4114095/how-to-revert-git-repository-to-a-previous-commit  (git revert syntax, and use cases)

##### New GIT commands used

```
1. git log  (view commit history, messages, and SHA ids for each commit. type 'q' to quit)
2. git reset --soft HEAD^  (roll back to previous commit, leave changes staged)
3. git reset --hard HEAD^  (roll back to previous commit, unstage changes)
4. git reset --hard theSHAid  (roll back to any commit. WARNING: re-writes git history) 
5. git revert --no-commit theSHAid..HEAD  (revert from HEAD to any previous commit of your choice, just replace theSHAid with the actual SHA hash from the git log)
6. git revert --continue  (continue forward with your revert. Creates revert commit)
7. git pull repoName theSHAid  (pull previous commit from remote repository)
8. git commit --amend -m "new commit message"  (change your previous commit message)
```

## Video 7 : Git workflow 2.0, debugging and organizing larger GIT projects. 
In this video, I'll show you how to avoid having to debug large branches with multiple merge conflicts, how to compare and sync up branches in advance to avoid merge conflict disasters, how to compare two separate branches against their parent branch, and how to combine your commits together to keep things organized. You'll also learn a more advanced GIT workflow that will allow for faster development. 

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=K_ndShku7og) 

##### Helpful Links

1. https://git-scm.com/docs/git-diff  (git diff in detail, additional use cases and options)
2. https://git-scm.com/docs/git-rebase  (git rebase, maximum level detail)
3. https://nathanleclaire.com/blog/2014/09/14/dont-be-scared-of-git-rebase/  (git rebase, informal guide)

##### New GIT commands used

```
1. git diff branch1..branch2  (compare differences between two branches)
2. git diff branch1...branch2  (compare branch1 and branch2 against their parent branch)
3. git diff branch1..branch2 >branchlog.txt  (compares two branches, creates branchlog.txt if it doesn't already exist, and prints the output of the branch differences to the text file)
4. git diff HEAD  (compare current directory to last commit)
5. git push repoName --delete branchName  (delete a branch named branchName that exists on your remote repository)
6. git rebase repoName/branchName (merge from repoName branchName into your current branch without creating a merge commit. places your commits at the top in the history line)
7. git rebase -i HEAD~5  (combine previous 5 commits into one commit. WILL OPEN VIM, use esc, i, :w, :q)

```

## Video 8 Documenting/tagging your code + GIT commands in depth.
In this video, I'll be explaining how versioning works, and why it matters.

##### Video Link
[![](img/youtube_logo.png)](https://www.youtube.com/watch?v=flSRyAraKb4) 

##### Helpful Links

1. https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet  (README.md syntax cheat sheet)
2. http://www.writethedocs.org/guide/writing/beginners-guide-to-docs/  (an article on why documentation matters)
3. https://git-scm.com/book/en/v2/Git-Basics-Tagging  (git tagging in depth)

##### New GIT commands used

```
1. git tag -a v0.0 -m "message" (assign a version number of 0.0 and a message to a commit.)
2. git tag  (view existing tags)
3. git show v1.0  (show version 1.0 and associated information)
4. git tag -d v0.0.1  (remove a tag)
5. git --help  (brings up help menu and displays common options)
6. git commandName --help  (display full manual on usage of specified command. Press q to exit doc)
```
