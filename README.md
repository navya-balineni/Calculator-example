To copy the code from local repo to remote github repo,we perform following commands in cmd.
Use git init- To create a local repository.
To create a file name, use notepad filename.txt, write the code and save it.
To keep track of the file, we need to perform - git add filename.txt.
To commit the changes, perform - git commit -m"Add Message".
Now, we need to push the piece of code into remote repository.
Perform - git remote add origin <ssh url>. (ssh url is the remote repository url)
To push, perform - git push -u -f origin master. (master-branch name)
If you made any changes in local repository file and perform push, the changes can also be seen in the remote repository file.
