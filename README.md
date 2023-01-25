# Demo

Let's take a look on how it change.
This is an example of how to use this.

You can change many of this things by typing in here.


## Commitming changes on GitHub via local

Making this more locally we are going to make some changes from the visual studio. 

Because I change this file while adding the above description, we have to save the changes on GitHub

1. First we need to use the _git status_ command, which shpws me all of the files that were updated, created, or delated but haven't been saved in a commit yet.

For example:

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

no changes added to commit (use "git add" and/or "git commit -a")

Untracked means that git doesn't know about the file.

You can add it by _git add ._ to adding all the existing changes or only by typing the name of the file you want to add: _git add index.html_

next we check again the status and notices that the files are ready to be committed. For this purpose we use _git commit -m "Added index.html" -m "some description"_. the first m denotes the tittle meanwhile the seconds describe the descrption of the changes. 

Clicking enter we save the changes locally. It isn't online yet. For these we use _git push_ with two more arguments which are _origin_ and _master_ (en mi caso solo git push, también sólo subió los cambios realizados que guardé en el local, no hasta donde voy.)
