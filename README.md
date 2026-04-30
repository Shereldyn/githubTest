# githubTest

# making changes

Git is the most widely used version control system in the world. Version control is a system that tracks changes to files over a period of time.

The working directory is where you make changes to your files. It is like your workspace holding the current state of your project that git hasn’t yet been told to track.

The staging area, or index, is where you prepare your changes before committing them.It’s like a draft space, allowing you to review and adjust the changes before they become a part of the project’s history.

Your local repository is your project’s history stored on your computer. It includes all the commits and branches, acting as a personal record of the project’s changes.

A remote repository is a version of your project hosted on the internet or a network. It allows multiple people to collaborate by pushing to and pulling from the shared resource.

Branches are parallel versions of your project. They allow you to work on different features or fixes independently, without affecting the main project, until you’re ready to merge back into them. 

A pull request is the way to propose changes from one branch to another. It’s a request to review, discuss, and possibly merge the changes into the target branch, often used in team collaborations.

And finally, merging is the process of integrating changes from one branch into another. It combines the histories of both branches, creating a single unified history.


Open up your terminal, run the command “git”, and you should see a list of all the commands available.


To configure git once downloaded use these commands:
“git config --global user.name”, space, then your username in quotes like this.

“git config --global user.email”, space, and then your email address,

This tells git who made the change and gives you credit for the work that was done. If we run “git config”, you can see all the other configuration options that are available(didn't work)

For now, we can check our settings by running “git config --list” and this will return the configuration options we just set. 


basic terminal and git commands so you can start using the tool
open terminal and type
“mkdir git-practice” to create a new folder.
“cd git-practice” to go into the folder that you just created.
"code ." to open the folder in a code editor. 
“touch hello.md” to create a new markdown file in our folder. (was not working 6.13)