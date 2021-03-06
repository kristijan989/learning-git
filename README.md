# learning-git

**Preconditions:** 
-  Create Word or any other document where you are going to collect all commands that you are going to type in these exercises below. That document will help us to track your work and solutions, so don't forget to save it. 
-  Download and install git (https://git-scm.com/downloads). There is also built-in GUI tool that comes with this installation, but I suggest downloading and instaling https://atom.io/ which is simpler and easier to work with (for example use it to resolve merge conflicts in exercise 4) 
-  During all these exercises you may have some issues to do what is requested or to get some errors. There are some tricky requests added on purpose (even in the beginning), to force you to investigate on the internet how to resolve, to be proactive and to understand git.

1. Exercice: 
   - Create public repository on your github account 
   - Create a directory on your computer that is going to contain the project and initialize it for git 
   - Add one yourFullNameCase.txt file in that directory and commit changes (add your first name and last name in file name) 
   - Connect your local repository to public repository that you have created in first step 
   - Push all changes to master branch

2. Exercice: 
   - Switch remote repository to point to https://github.com/kristijan989/learning-git and pull changes 
   - Create your own branch (name it to be unique branch yourfirstname-yourlastname) 
   - Add two files in the root project directory: yourNameFile1.txt and yourNameFile1 - Copy.txt and add both to staging 
   - Commit only file yourNameFile1.txt and push changes to your remote branch
   ```
   **Hints:** 
     Check with git status what is ready to be commited 
     Be carefull to set correct remote branch for pushing changes 
     Use -help to see git options (for example git commit -help)
   ```

3. Exercice: 
   - Ignore unwanted file yourNameFile1 - Copy.txt from repository Hint: *use check-ignore option to see if your file is marked successfully as ignored file

4. Exercice: 
   - In browser go to github repository https://github.com/kristijan989/learning-git and switch to your branch. Go to edit yourNameFile1.txt directly from github (add text: This is remote change to file) and commit changes from there 
   - Go back to your repository directory on your computer and find file yourNameFile1.txt. Open it in any text editor (notepad, etc) and add text in two rows: 
     ```
     This is local change to file 
     This is second line change 
     ```
     Open again git console and check git status. What you see? Try to commit and push change. Is it done? If not than read carefully what error you got and try to follow steps that are suggested. Fix conflict so your file looks like: 
     ```
     This is remote change to file 
     This is second line change 
     ```
   - Commit and push changes to remote branch

5. Exercice: 
   - Once you are done with previous exercises enter your name and branch name in file Candidates.txt on your branch, commit and push changes to your remote branch. Create pull request in Github, add Kristijan as review-er and be ready to get comments that you should resolve in order to do a merge of your branch to master branch.
