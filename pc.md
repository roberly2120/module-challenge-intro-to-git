## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open source program for tracking changes in text files.  
2. What is the difference between Git and GitHub?
Git is where code is created or edited locally on a computer while GitHub is a place where that code is stored online. 
3. Why do we create a branch?
We create a branch to edit existing code separately from the main branch so that it can be reviewed before being added to main.
4. What is the purpose of a Pull Request?
A pull request lets your team/lead know that you have made changes to code that need to be reviewed.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git merge applies changes from one branch into another, which can be done with a pull request or from the command line. 
git pull adds and commits changes from the remote repository to your local branch. 
git fetch adds changes from the remote repository to your local branch but allows you to review those changes before commiting them. 
7. What is a merge conflict?
A merge conflict occurs when there are differences in the same line of a file between two copies that are trying to merge, or when one person edits that file and another deletes it. 
8. How do you resolve a merge conflict?
To resolve a merge conflict, you choose which changes will be incorporated from each different branch into the new commit. For merge conflicts caused by competing line changes GitHub can be used to 
resolve them. For all other types of merge conflict the CL needs to be used.
