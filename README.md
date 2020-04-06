# graphsRfiles
We use this repository for:
1. R files to try igraph
2. record additions

To clone repository on your computer download GitHub Desktop https://desktop.github.com/ 


## Instructions for GitHub (Mac)
Brian's Instructions:

To clone this repository on your local machine (Mac):

Install git from: https://git-scm.com/downloads

Create ssh private/public keys (for Mac). In the terminal, type this, replacing YOUR EMAIL:

ssh-keygen -t rsa -C “YOUR EMAIL"

Keep pressing enter ask it asks for location and passphrase. From the terminal, run:

cat ~/.ssh/id_rsa.pub

Copy and paste everything that is output (from ssh-rsa to your email address).

Go to GitHub.com, click your avatar in the top right, Settings, then click “SSH and GPG keys” on the left side of the screen. 

Click “New SSH key” and paste the key into the big box. 
The title can be anything, and it is linked to your computer. 

Click “Add SSH Key.” Now go to terminal and run:

ssh git@github.com

If necessary, type “y” to continue connecting. 
You should get a message that you have successfully authenticated, but GitHub does not provide shell access. This is ok.

Now, to download the repository, go to terminal, use cd to change to the directory where you want to store the repository (on a Mac, you can type cd, then drag the folder to the terminal window), and run:

git clone ssh://git@github.com/SFRG-SJU/graphsRfiles

This should create a copy of the repository in a folder called “graphsRfiles” in whichever directory you had the terminal pointed to when you executed it.

------------------

## Instruction for Visual Studio Code

On left sidebar click Explorer (top option).

Click Open Folder and choose the "graphsRfiles" folder.
This now lets you choose and edit existing files in the repository.

On left sidebar click Extensions (5th or bottom option).

Search and install R 
Search and install LaTeX Workshop


To Commit changes from Visual Studio Code: 

On left sidebar click Source Control (3rd option)

Select the modified file and click the check mark on the top line where it says SOURCE CONTROL.
In the pop-up window you need to type a brief description. 

At the bottom left next to 'master', click the up and down arrows to push/pull committed files to and from the GitHub repository.
