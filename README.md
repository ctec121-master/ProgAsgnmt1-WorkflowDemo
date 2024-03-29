# Programming Assignment1 - Workflow Demo
## Purpose
* Verify ability to clone repsitory from GitHub Classroom
* Verify ability to update assignment
* Verify ability to push finished assignment back to GitHub.

# Repo Contents

The reposiotry contains the following files:

- **README.md** - This file. It's a file written in the Markdown language.
- **MarkdownSyntaxGuide.md** - A short introduction to Markdown
- **helloWorld.py** - The Python file that you will be updating.
- **.gitignore** - This file tells git to ignore hidden files or others that are generated by Python when it runs.

# Steps to Follow

1. Open hello.py in VS Code
2. Run the file to verify that everything is OK and you get the expected output.
3. Update the message in the print statment to say "Hello, Bill"
4. Create a new Python file named "myFile.py".
5. Create a function that prints some message and call that function. The structure is the same as hello.py, but with your own function name and message.
6. Run the file to verify everything works. Fix any bugs and rerun until the code is working.

This completes the coding part. Now you need to Stage, Commit, and Push your finished product.

## Submitting Your Solution

There are several stages in submitting your work.

### Staging

1. In VS Code click on the **Source Control** icon. It's the icon that looks like a tuning fork, the third from the top.
2. You will see some letters on the right margin. **M** means the file has been modified. **U** means that the file is "untracked" or new.
3. Hover your mouse over an individual file or over the "Changes" title. You should see a **+** sign appear.
4. Click on the + sign. This will stage your changes. In other words you are selecting the content you want to commit to the repository. A new title will appear named "Staged Changes".

### Committing

1. In the textbox above the "Staged Changes" title, type in your **commit message**. This message should describe the changes you have made. Note VS Code gives you a 50 character limit on the message.
2. Above the message is a check mark. Click it. If you haven't staged everything you will get a message asking you what to do. You can commit just the staged files or you can commit everything (it will stage any remaining unstaged work beofre the commit).
3. This has saved your changes to your **local repository**. The next stage moves them up to the GitHub repository

### Pushing

1. Bring up the VS Code command palette. Select Git: Push. This may bring up a login dialog. If so enter the email address you used to setup your GitHub account and your password. You may get a message at the lower right about running git fetch periodically. Answer NO.
2. To check to see if your changes made it to GitHub, go to the URL of your repository in your browser. You should see updated statistics (number of commits) and updated descriptions with the files you committed. 
3. At this point the instructor can see your work in GitHub using his/her classroom account. There is nothing you need to do in Canvas.
