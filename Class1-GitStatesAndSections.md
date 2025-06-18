Git exists to archive and organize the various states of a program as it undergoes development.
</br></br></br>
There are three states files can exist in...
* changed (referred to as modified)
* In line to be archived (referred to as staged)
* archived (referred to as commited)
</br></br></br>

Additionaly there are five Git "sections", below we explain why they exist and how they interact with git.
1. The Workspace
   - The workspace is the only section where you can edit and modify git files. If you have access to a Git repository—local or remote—you can check out any of its branches and work with them here. Modified files sit here until they are staged.
2. The Stash
   - When you need to open a different branch, but still have modified files in your Workspace, that is when you use the Stash. It exists to provide you a temporary storage alternative to commiting WIP files.
3. The Index
   - This is how git protects developers from themselves. If changes arent added to the Index they wont end up in the local repo after you commit. It exists to prevent accidental file corruption or modification. Staged files sit here until they are commited.
4. Local Repository
   - This is the git archival system on your computer. It is a database of all commits, and keeps track of which commits belong to which branch. We will talk about how exactly git keeps track of these branches soon.
5. Upstream Repository
   - This is the distributed git archival system. It is a database of all commits made by all users to the upstream source (generally a server hosted by a provider like github), Behaves very similarly to the local repository.

To get a more comprehensive understanding of how files move around git, play around with the website linked below. I personally recomend bookmarking it.

https://ndpsoftware.com/git-cheatsheet.html#loc=workspace;
