How to add a project to GitHub from PyCharm:

After you have created your project in PyCharm, you will need to add two files to the project before you can share it on GitHub.

First is a “README.md” file, this is a simple text file and you should enter your readme message for your project here.

Next we need to add “.gitignore” 

Copy the content from the “GitIgnore.docx” and simply paste it into the file that you create in your project. The reason for the GitIgnore is PyCharm will try to add an .idea file to your repository. If this is added it will cause problems with your project each time you try to upload it or download it from the repository.


 Now that you have added these files go to the VCS tab at the top of PyCharm. Under the VCS tab scroll down to “import into version control”, then “share project on GitHub”.



This will bring up a pop-up asking you for a New Repository name and it will automatically fill in the box with the Project name. Don’t change this name, give it a brief description. And then click share.




On the next pop-up box that appears it is asking for the initial files to commit, all of them should be checked and since this is your first commit leave the message as initial commit.

