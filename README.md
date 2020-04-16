# Create-new-branch-locally using GIT BASH
The repo shows how to create new branch locally to control separate feature in your project and push that branch on GitHub as well.
1. Create new branch
  - Go to your Git repository in your PC. Right Click and choose 'Git Bash Here'.
  
  - OPTIONAL - List all your branches
    - ```$  git branch ```
     - OR__
    - ``` $ git branch -a ```
  - Create new branch
    - ```$ git branch <name of your new branch>```
2. Checkout new branch
   -  ```$ git checkout <name of your new branch> ```
   
3. Commit any changes to your new branch. (CAN BE SKIPPED)
  - Check status
    - ```$ git status ```
	
  - Adding files
    - Add all of them ```$ git add .```
	
    - Add specific file. See your file name in the list of modified files using $ git status 
	```$ git add 'your filename'```
	
    - Restore file. See your file name in the list of modified files using $ git status. 
	``` $ git restore 'your filename'```
	
4. Push new branch to GitHub <br />
	```$ git push origin <name of your new branch>```
