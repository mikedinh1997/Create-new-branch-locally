# Create new branch locally using GIT BASH
The repo shows how to create new branch locally to control separate feature in your project and push that branch on GitHub as well.
### Create new branch
  Go to your Git repository in your PC. Right Click and choose Git Bash Here.
  
  - OPTIONAL - List all your branches
    ```$  git branch ```
	or
``` $ git branch -a ```
	
### Create new branch
   ```$ git branch <name of your new branch>```
   
### Select new branch

  ```$ git checkout <name of your new branch> ```
   
### Commit any changes to your new branch. (CAN BE SKIPPED)
  - Check status
    - ```$ git status ```
	
  - Adding files
    - Add all of them ```$ git add .```
	
    - Add specific file. See your file name in the list of modified files using $ git status 
	```$ git add 'your filename'```
	
    - Restore file. See your file name in the list of modified files using $ git status. 
	``` $ git restore 'your filename'```
	
### Push new branch to GitHub <br />
   ```$ git push origin <name of your new branch>```
