GIT-
disrributed version control…
distributed-multiple people work on it..
version-make changes and update..
now to fork someone code and work on that remotely in your machine do the following thing
fork and then copy the url at the top and clone it using git clone..
terminal commands

cd~ —>shows everything in the computer
cd Documents —>it will navigate to Documents 
ls —> shows everything inside Documents
mkdir gitlearn —> make a directory in  the name gitlearn
git clone https://github.com/narayanamo/learn-git —>will clone this file from online to local machine...
cd gitlearn —> go to the folder gitlearn
cd.. —> opens the previous folder which u have been
git status —> shows the current status and changes made
touch superFun.txt —>makes a new file called superFun.txt
now if we do git status —>shows the file in “red”color irt means it is added to the repository
git add superFun.txt —>now the terminal shows file in green color when we do git status..
STEP 2:
git commit -m “this is my first commit —>shows  your branch is ahead of ‘origin /master’
git push - will push the content to the git repository..
git status-shows your branch is up-to-date with ‘origin/master’..
now the file superFun.txt is added to the narayanamo repository..

SO NOW HOW TO FORK SOMEONE PROJECT AND MAKE CHANGES TO IT AND PUSH IT TO YOUR GITHUB ACCOUNT…
1.fork the project of someone by clicking on fork button..
2.and select your github account (and now it would show your username/projectname)
3.in terminal type git clone copy the url and paste [hint:the url will have your name]
4.now the project will be in your local machine..
5.create a file by using touch
6.git status would show the file in red color
7.now git add -A or git add filename.txt will show file from red to green
8.git commit “fun commit”
9.git push
10.now refresh your github page we can see new file added..
NOW HOW TO PUSH CHANGES WE MADE IN ALREADY EXISTING FILE
1.once you made changes do git status will show files in red color..
2.git add -A will change file from red to green
3.git commit -m “more awesome code”
4.git push
now the changes that are in the local machine in brackets will go to online github account..
FEW MORE COMMENTS
git rm -rf fun.txt —> will remove that file from git
<!-- NOW TO CREATE A REPO AND ADD A PROJECT FROM LOCAL COMPUTER-->
1.NAVIGATE TO YOUR FOLDER
EG: CD DESKTOP
cd learningGit
2.git init
3.git status(to track the file changes)
4.git add -A else git add filename
5.git status(the filename in green color)
6.git commit -m "my commit"
7.git remote set-url origin (url copy from https)[already exsisting repository]
8.git remote add origin (url copy from https) [this is to add file to a new repository created by clicking + on top of the page]
9.git push origin master
10.now the files get added to the repository







