# intropython


## 23.04.2025


* potatoes
* brew is package manager mostly used Commandline apps (can use for software stuff) most software installed with brew but cannot switch between versions
* asdf is software version manager (need to be able to run multiple python and switch between seamlessly)
    * we installed python using asdf
    * ignores single new lines so if want to add new line must add more than 1 new line also must space after '*'

    when using terminal you can use the "arrow key 'up'" to copy previous line into new line created based on the amount of ups cllicked
    * when execute terminal file 3 things
    1) checks to see if binary file- if so executes as program
    2) checks if shebang (#!) if this exists it will execute file using program given by shebang
    3) if no shebang will run as shell script (fun trivia for much later!)

    * in this case env= environemnt and used to have computer find python in system to run program

* git init creates new repository
    * the git status shows current state of git repository

    * untracked files means files are recognized but not tracked/stuff being done about files
    * whenever the file reads under "change is to be commited" then it is committed



    *  to commmit staged files (the random numbers and letters are commit identifier) and use 
    git commit -m "message here"

    * git log shows history of commits

    * git branch shows what branch you are in

* git chechout -b (name of branch)     allows you to create new branch and go to new branch in same line

* this can modify files and git will acknowledge the need to commit to history and need to track - to track it 

if done commit then "git log" will show multiple commits and most recent commit will be first, in descending order

* git checkout     switches between branches and branches will be at different points in history

* git merge name of branch        merges what has been commited
*  git branch -d name of branch     deletes branch
* git tag -a v1 -m "name of tag"      a is the name of the tag        m is the description of the tag

* 23.04.2025

* idea of project

* dependencies when you make your project use another persons code

 * pip installed with python (old slow clunky)
 *  UV is the new system that 

 * process was UV entered and then ended the terminal (below secionn)

 * in a terminal a . means a current folder

 * do not commmit .venv

 * commit the uv.lock

 * to tell git to forgot .venv

 * if you want to create a new project in python you type:    uv init nameoffile

 type in name of file or thing in gitignore and git will ignore the folder listed

 * if you click the + in the changes section you are getting ready to comm