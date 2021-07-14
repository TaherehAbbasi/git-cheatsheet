Devops 1 - Exercise No. 4 Development
Exercise Title: Working with GIT
1. Why do we use version control tools like Git?
2. Git is a version management tool that controls the program source so that it can have a base for maintaining the program source and system versioning.
3. What is a repository? What important files does a good repository have?
It is a repository that contains a collection of commits and branches that we have created on our project code and items such as tags. A good repository includes three important files LICENSE, README.md and .gitignore.
3. What are the parts of a good document?
It is composed of three parts. The first part states what this project is and what it is for. The second part states how to use that project. The third part states that if someone wants to help in this project, How should he do this? This step is optional and not mandatory in the title.
4. What does the clone git command do?
With this command, it takes a project from the git hub, for example, and places a sample of it on the system.
5 . If we want to update the local repository with the remote repository, what command should be executed?
If you have fetched "$ git pull rebase" can be done. Otherwise, the “ $ get pull “ command is appropriate.
6. What is the difference between reset, revert, checkout?
A revert is a rollback that causes a new commit to be made. A checkout is a rollback that causes nothing to change and only checkout to a specific point. reset causes the changes to return and the commit to be removed.
7. What is the difference between merge and rebase?
merge causes a new commit to be created.Rebase causes if there are changes in the reference remote ,We can rebase and paste them in order.
8. What command is used to view the history of committees?
“ $ git log “ command.
9. If we want to see the changes of a file, what command do we use?
“$ git diff HEAD” command.
10. What is the use of tag? How to create a tag?
If the program has a tag, you can create a release from the tag.
For example: $ git tag v1.0.1.
11. What process must be followed to participate in a project that is managed with the git?
$ mkdir test   //   Create a directory for our project
$ cd test   //   entered the directory
$ get init   //   init the git
$ touch LICENSE   //   Create the license file
$ touch README.md   //   Create the document file
$ touch .gitignore   //   Create a file to ignore some important things
$ git add.   //   We add three important previously created files to the git
$ git commit -m "first commit"   //   we do the commit

12. What are the branches used for and how can they be integrated?
It is a directory on which the desired work is done and it is possible to have several branches in the git. And with the ” $ git merge”  command, the branches can be merged.

