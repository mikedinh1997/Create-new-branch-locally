# Create-new-branch-locally using GIT BASH
The repo shows how to create new branch locally to control separate feature in your project and push that branch on GitHub as well.
<br />
1. Create new branch <br />
  - Go to your Git repository in your PC. Right Click and choose 'Git Bash Here'. <br />
  - OPTIONAL - List all your branches <br />
    - $ ``` git branch ``` <br />
    -OR <br />
    - $ ``` git branch -a ``` <br />
  - Creat new branch <br />
    - $ ``` git branch <name of your new branch>```
<br />
2. Checkout new branch <br />
   - $ ``` git checkout <name of your new branch> ```
<br />
3. Commit any changes to your new branch. (CAN BE SKIPPED) <br />
- Check status <br />
  - $ ``` git status ``` <br />
- Adding files <br />
  - Add all of them <br />
   - $ ```git add .```<br />
  - Add specific file. See your file name in the list of modified files using $ git status. <br />
   - $ ```git add 'your filename'``` <br />
  - Restore file. See your file name in the list of modified files using $ git status. <br />
   - $ ``` git restore 'your filename'``` <br />
      
4. Push new branch to GitHub <br />
  - $ ```git push origin <name of your new branch>```
