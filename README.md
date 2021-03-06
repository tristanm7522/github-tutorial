# GitHub Tutorial

_by Tristan Molina_

---
## Git vs. GitHub
**Git** is a _system of files_ that keep track of any changes you made in them. **Github** provides repositories where you can _store and share_ your code and work with the world, or keep it to yourself. **Github** also has it's own website which is easier to use. Signing up to Github is a one time thing just like an email. Just remember your username and password.

 Click to go to [Github Website](http://www.github.com)


---
## Initial Setup
After setting up a Github account you can set up a new SSH key. On the IDE website you are using like [Cloud9](https://c9.io) click the settings button (May appear as a gear) while on the home page. While in the settings you will see an SSH keys tab, click it to see your SSH key, Copy the SSH key it gives you (it will appear as a whole bunch of letters and numbers but don't worry your not being hacked or anything he he) Now that you have the SSH key go to [Github.com](http://github.com) and go to your settings into the SSH key tab. Now click the _add SSH key_ button. Add a title such as _Cloud9_ then paste your SSH key inthe box that says SSH key or just key. Press add and you now have your SSH key one time setup complete.

---
## Repository Setup
Now to set up your repository you neet to return to your IDE. In you perfered directory use the code **git init**. After that you will need a _new repository_. To create a repository you must click your profile avatar or the **top right of the webite** to open it's drop down meñu. Click **"Your profile"**. Now you should be on a new page, you should see three tabs near the top of your screen. One of these tabs is labled **"Repositories"**. Click Repositories to continue to the next step. Now you shoud see a _green button_ that says **"New"**, click on it to create a new repository. Your _repository name_ should be the same as your file name on your IDE. remember to keep it simple. When you are finished press the _green_ **"Create Repository"** button. Now you will see a whole bunch of code you can copy and paste ito your command line but first you must make sure you are inside your folder. To move into a created folder use this command "cd name of your folder". Now type the commands under "**...or create a new repository on the command line**" one by one, line after line.


---
## Workflow & Commands
Here are four need to know commands when using git.

1. git status - Tells you if there are any files added and need to be commited, also tells you the code to commit a sile or all files.
2. git add - Allows you to add a file to be commited. To add a file you must be in the same directory that the README.md is in and the README.md must be saved before added.
3. git commit -m "" - This code allows you to commit the file you added so now it may be pushed a repository. To use it you must have a file already added. Inside the quotes I put in the code you can add what you want such as what you changed,added or deleted.
4. git push - this command will take you commited file and push it up to the repository it belongs it on gihub.

Here is some markdown syntax to use when writting in your README.md files to make it look more professional and easy to read.
###Markdown Syntax
+ **Headings**

To create headings you need to use this symbol #. Headings have 6 levels. the hight the level the smaller the heading and less # required. To create a heading you need to put a # before the work or sentence you wish to make a header. Here are some examples of all header levels.
#Level 1
##Level 2
###Level 3
####Level 4
#####Level 5
######Level 6

+ **Bold Text**

To make your text bold you must use the star symbol twice on each end of the text you want to be bold. In the end the text will look like this "**important**".

+ **Italacized Text**

To make text italacized you need to put an underscore one each end of the text you want to italicized. In the end the text will look like this "_kinda important?_".