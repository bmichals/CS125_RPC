# CS125_RPS GitHub Guide

RPS GitHub Guide

Setting up your local files

Sign up for github if you haven’t already at github.com


Open terminal on your computer and install homebrew: https://brew.sh

For mac and linux run: 

$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Run line in terminal: $ brew install git

Open the github repo in your browser, click the code button and copy the HTTPS link



Then, cd into your desired parent directory and run

$ git clone ​​https://github.com/bmichals/CS125_RPS.git

Make sure you are using the “main” branch. There is also a “master” branch. Branches are generally used for different versions and trials so we may decide to commit to different branches as our workflow evolves. But for now, let’s all work in the main branch.

If the main branch files are not showing up after cloning the repo try this in your terminal:

$ git checkout main

The files should now show up. Also do this if you are trying to push commits and they are not showing up in the main branch of our repository, you are likely operating in a different branch.


Commands to update files

To get the most recent version of our files on your device

First cd into your local folder
Then put in the terminal:

$ git pull

The terminal should either update your files or say “Already up to date.”


To put your updated files onto github

First save the most recent version of your files
Then in terminal write:

$ git add (file or folder name(s))

Or to update everything:

$ git add .

Then commit your changes with a label detailing what you changed

$ git commit -m “LABEL OF YOUR COMMIT”


Push your commit to the github repository

$ git push


Your updated files should now be in the github for others to pull. Check to make sure they’re there and text the slack that you’ve pushed a new commit.


