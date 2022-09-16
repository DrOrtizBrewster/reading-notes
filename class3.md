# What I Learned in My Readings

## Class Three Notes

* Visual Studio Code - VS Code works hand-in-hand with your computer's terminal
* You can create a link in VS Code by using brackets around the word or words that you want linked and the file name in parenthesis.
* The file name will be linked to the word or words.
* USE A C P to get information pushed up.
* A is for git add
* You can add a page or all at one time after the phrase git add
* git status will tell you where you are in the process
* git restore should be used sparingly
* C is for git commit with a dash and m "phrase here" will show you what changed.
* P is for git push with the words origin main
* You can also use git push origin and the word main
* Git config pull.rebase false - could help to merge items in VS Code & terminal to github

### Seeing Your Remotes

Seeing Your Remotes
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

$ cd example

$ git remote -v

remote1 <https://github.com/remote1/example> (fetch)

remote1 <https://github.com/remote1/example> (push)

remote2 <https://github.com/remote2/example> (fetch)

remote2 <https://github.com/remote2/example> (push)

remote3 <https://github.com/remote3/example> (fetch)

remote3 <https://github.com/remote3/example> (push)
Adding Remotes
To create a new remote Git repository with a short name, use the following format:

git remote add shortname url
Example:

$ git remote

origin

$ git remote add js <https://github.com/janesmith/project1>

$ git remote -v

origin <https://github.com/johndoe/project1> (fetch)

origin <https://github.com/johndoe/project1> (push)

js     <https://github.com/janesmith/project1> (fetch)

js     <https://github.com/janesmith/project1> (push)
This addition of these remote and short names allows you to use shortnames for Git collaboration.
