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

### Choose one correct answer for each statement

1. **Version Control** is a system that allows you to revisit various versions of a file or set of files by ***highlighting or recording*** changes.
2. **Centralized Version Control** system uses a single server to store all changes and file versions, which can be accessed by ***one or various*** clients.
3. **Distributed Version Control system** addresses the vulnerability of the CVS being the single point of failure. It allows for multiple mirrored ***servers or repositories***, which allows programmers to collaborate.
4. Is **Git** a ***CVS or a DVCS***?
5. **Git** mostly relies on ***server or local*** operations.
6. What are the **three main states** for Git files?
7. What is one command that can be used to get help in Git?

#### Correct Answers

1. recording
2. various
3. repositories
4. DVCS
5. local
6. Committed, modified, staged
7. git help command or git command --help or man git-command

## MORE NOTES FOR ME

Setting up a Git Repository
Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:

$ cd test (cd = change directory)
Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”
Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.

Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone on <https://github.com/test>
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone <https://github.com/test> mydirectory
The command above makes a copy of the target repository in a directory named “mydirectory.”

Workflow
Local Repository Structure
The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit
image03

Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

Tracked

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

The Life Cycle of File Status
After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.
Then, you commit staged changes.
image00

Check File Status
To determine the state of files, utilize the git status command:

$ git status
On branch master

nothing to commit, working directory clean

*This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.

Tracking and Staging a New File
Single File

Track one file only by using the following format:

git add filename
All Files

Track all files in a repository by using the following command:

$ git add *
*After using these commands, files are tracked and staged for committing.

After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:

$ git status

On branch master

Changes to be committed:

  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.

Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”
*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.

Committing All Changes
$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.

Pushing Changes
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example:

$ git push origin master
*This command pushes changes from the local “master” branch to the remote repository named “origin”.

*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.

Git students also learn
Stashing Changes
When you are not ready to commit changes but do not want to lose them either, git stash is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.
