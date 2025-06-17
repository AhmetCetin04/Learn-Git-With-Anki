Git exists to archive the various states of a program as it undergoes development.

There are three states files can exist in...
* changed (referred to as modified)
* In line to be archived (referred to as staged)
* archived (referred to as commited)

Beyond the states our files can have, there are five sections our files can reside within...
* Stash, where WIP files can temporarily be stored, in order to free up the workspace for other things</br>
    ↓↑
* Workspace, where modified files sit until they are ready to be staged</br>
    ↓
* Index, where staged files sit until they are ready to be commited</br>
    ↓
* Local Repository, this is where files are archived on your computer</br>
    ↓↑
* Upstream Repository, this is where files are archived on a server

The following is what your workflow with git will generally look like...
1. Get a repository, either by making one from scratch or downloading one
2. Delete, and edit the files within the Workspace
3. (Optional) Store the files from the Workspace into the Stash, this will reset the Workspace
5. (Optional) Retrieve the files from the Stash and place them back into the Workspace
6. Add the modified files, any new files, and deleted files you want Git to archive into the Index
7. Commit the staged files in the index to the Local Repository
8. Push your Local Repository onto the Upstream Repository

Bookmark this, it is great</br>
<a href="https://ndpsoftware.com/git-cheatsheet.html#loc=workspace;" target="_blank" rel="noopener noreferrer">git-visual-cheatsheet.html</a>
