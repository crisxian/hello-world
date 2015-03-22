☜ Git-it ☞
CHALLENGE
Commit To It

NUMBER
3 / 11

The Challenge:

Create a file in your new repository, add something to that file and commit those changes to Git.

Step: Create a New File

Now that you've got a repository started, add a file to it.

Open a text editor. Now write a couple of lines of text, perhaps say hello, and save the file as readme.txt in the 'hello-world' folder you created in the last challenge.

Step: Status, Add and Commit Changes

Next check the status of your repository to find out if there have been changes. Below in this terminal, you should still be within the 'hello-world' you created. See if there are changes listed:

$ git status

Then add the file you just created to the files you'd like to commit (aka save) to change.

$ git add readme.txt

Finally, commit those changes to the repository's history with a short description of the updates.

$ git commit -m "<your commit message>"

Step: Make More Changes

Now add another line to readme.txt and save.

In terminal, you can view the difference between the file now and how it was at your last commit.

$ git diff

Now with what you just learned above, commit this latest change.

Verify with  git-it verify
Go to the next challenge  git-it
Tips

Check status of changes to a repository
$ git status
View changes to files
$ git diff
Add a file's changes to be committed
$ git add <FILENAME>
To add all files changes
$ git add .
To commit (aka save) the changes you've added with a short message describing the changes
$ git commit -m "<your commit message>"
REPOSITORY
⤶
GITHUBBIN
⤷
GIT-IT CHALLENGES ABOUT DICTIONARY RESOURCES OPEN AN ISSUE

hello, world