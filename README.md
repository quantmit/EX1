Exercise 1: creating a repository (go down for more)
In your RR_git1 directory, initiate a git repository named EX1
(hint: you can either initiate it with that name, or create folder named EX1, enter it, and initiate the repository inside)

git init EX1

cd EX1

List all available configuration options.
git config -l

List all global options
git config -l --global
(Note: this will only work if you’ve ever changed any global options)

The three git states
Unlike the other VCS, Git has something called the “staging area” or “index”. This is an intermediate area where commits can be formatted and reviewed before completing the commit.



Source for this and following slides: https://git-scm.com/

The three trees
See here for a detailed description
And think of a tree as an ordered collection of files.

Tree	Role
HEAD	Last commit snapshot
Index	Proposed next commit snapshot
Working directory	Sandbox
