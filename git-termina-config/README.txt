https://classroom.udacity.com/nanodegrees/nd004/parts/fe81273e-394c-492a-892e-664bd3cc9d4a/modules/52c93310-7bd7-4c47-a17f-7af42cfb54d6/lessons/1b369991-f1ca-4d6a-ba8f-e8318d76322f/concepts/63a6f935-dea7-43c2-aaa3-61deea5070c8



Configuration Steps
To configure the terminal, we'll perform the following steps:

download the zipped file from the Resources pane, or the bottom of this page
move the directory udacity-terminal-config to your home directory and name it .udacity-terminal-config (there's a dot at the front, now!)
move the bash_profile file to your home directory and name it .bash_profile (there's a dot at the front, now!)
if you already have a .bash_profile file in your home directory, transfer the content from the downloaded bash_profile to your existing .bash_profile

First Time Git Configuration
Before you can start using Git, you need to configure it. Run each of the following lines on the command line to make sure everything is set up.

# sets up Git with your name
git config --global user.name "<Your-Full-Name>"

# sets up Git with your email
git config --global user.email "<your-email-address>"

# makes sure that Git output is colored
git config --global color.ui auto

# displays the original state in a conflict
git config --global merge.conflictstyle diff3

git config --list
Git & Code Editor
The last step of configuration is to get Git working with your code editor. Below are three of the most popular code editors. If you use a different editor, then do a quick search on Google for "associate X text editor with Git" (replace the X with the name of your code editor).

Atom Editor Setup
git config --global core.editor "atom --wait"
Sublime Text Setup
git config --global core.editor "'/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl' -n -w"
VSCode Setup
git config --global core.editor "code --wait"
