# Markdown & Git 

# What is Markdown?
- **Markdown is an easy way to style text on the web.**
- **Markdown syntax consists of a plain text with a few symbols.**
- **Markdown controls the document display through many features, such as headers, tables, links and images.**
 
# What is Git?
- **Git is a distributed version control system that creates a snapshots of a file and stores a reference to it.**
- **Git operates locally, keeps track of file/directory changes and minimizes data loss.**
- **Git has three states: committed (data stored in a local database), modified(file has been changed; not commited) and staged(Flagged a file’s changed version to be committed).**
 
## Important terms & commands:
 
- Cloning a file: copies all versions of all files for a project.
- Clone a repository into a directory:
 >$ git clone https://github.com/test mydirectory
 
- Local Repository Structure includes the following:
- Working Directory: The actual files reside here.
- Index: The area used for staging
- Head: Points to the most recent commit
 
**Tracked files vs. Untracked files:**
- Tracked files: can be modified, unmodified, or staged
- Untracked files: were not in the last snapshot and do not currently reside in the staging area.
- $ git status (checks git status)
- git add filename (tracks single file)
- $ git add * (tracks all files)
- $ git commit -m “made change x,y,z” (commits and records a change)
- $ git commit -a (commits all changes)
- $ git push origin master (pushes changes to remote repository)
- Use git remote command to view the short names, such as “origin,” of all specified remote handles.
- Use  git remote -v command to view all the remote URLs next to their corresponding short names.