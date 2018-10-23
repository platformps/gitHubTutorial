# GitHub Tutorial

To set up Git and GitHub please attempt to follow these helpful tutorials. If you have trouble, feel free to message your instructor for assistance:

## GitHub Official Helpful Tutorials

https://help.github.com/articles/signing-up-for-a-new-github-account/  


https://help.github.com/articles/set-up-git/


## Non-Official Helpful Tutorials

https://dev.to/landonp1203/how-to-properly-set-up-git-on-your-computer-33eo

https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners


To test if Git and GitHub is set up correctly, please open your Terminal(Mac) or Command Prompt(Windows). Please type: git

If you get an error that says something along the lines of "command not found" something wrong and we need to fix your set up. Feel free to Google it, because chances are you will find 1000 other developer's potential solutions how they solved your exact problem.

If you were able to create your account and set up your environment successfully please proceed to the next section.

##  Let's Create A Repo!(repository)

1. Please click the Start A Project button on the GitHub homepage:

<img alt="github home page screenshot" src="images/startAproject.png" width="300">

2. I named my repo gitHubTutorial, I click create, and that brings me to this screen:

<img alt="empty repo screenshot" src="images/emptyRepoScreen.png" width="300">

3. I'm on a Mac, so I am going to open up my terminal (Windows please open your Command Prompt). Mac's Terminal uses Bash and Unix by default and Windows doesn't so we will have some slightly different commands depending on your OS (Operating System). Here is a screenshot of my terminal which will be followed by an explanation of each line.

<img alt="image of mac terminal with commands" src="images/screenshotOfTerminal.png" width="300">

When you boot up your terminal. It opens up in the root directory. But I would prefer to save my project on my desktop not somewhere in the root of my computer. To see the subdirectories and files of your current folder type: ls
and click enter.

cd desktop - This command opens my desktop folder.

Now that I'm where I want to be I will create a project folder.

mkdir ourGithubProject  - This command mkdir creates a directory named ourGithubProject. If you are currently in your desktop in your terminal, you will notice that after running this command a folder with the name ourGithubProject was just created. You can really name it whatever you like.

cd ourGithubProject - This command opens my ourGithubProject folder so now I am inside of it.

git init - Git explains that this command does the following "This command creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files. An initial HEAD file that references the HEAD of the master branch is also created." The way I think about it, git init simply starts a git project.

git remote add origin xxxxxxxxxxxxxxxxx.git - When I created my repository on Github.com, that brought me to an empty repo page. I copy the line that is highlighted, and paste it in my terminal. This line basically tells our local git repo (the repo on our computer) that it's corresponding Github.com repo lives at this URL.

touch README.md - This command creates (touch = create file)  a file named README.md (.md means that this file is a markdown file). GitHub looks for a file entitled READE.md at the root of every repo created which will basically be displayed to GitHub users viewing your repo online.

atom . - This command opens up my current directory in Atom (Atom is great free code editor useful for tasks like this one. More can be found about Atom at https://atom.io/)

Now that Atom opened, I am going to write some text in my README.md file. You can write plain old text in markdown. You can also make really fancy documents. Here is a helpful markdown tutorial: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

You can use markdown to make your repo more professional looking, provide instructions for running or cloning your project to potential viewers, or simply tell potential employers what your project is all about.

<img alt="screenshot of text in my atom editor" src="images/firstDraftOfCode.png" width="300">
