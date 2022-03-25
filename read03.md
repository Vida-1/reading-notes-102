# Read 03: Revisions and the Cloud
### Read:
-[Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)


## Notes

### 3/22/2022 Time to Git it Done! <img style="float: left;" width="400;" src="https://images.unsplash.com/photo-1618401471353-b98afee0b2eb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1488&q=80)">

<!-- [Image](https://images.unsplash.com/photo-1618401471353-b98afee0b2eb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1488&q=80) -->

##### - Git is an open-source distributed version control system development of which was initiated by Linus Torvalds in 2005 in an attempt to improve upon and replace (due to conflict with the makers of) BitKeeper. It has since become "one of the most utilized Version Control Systems in the world." ("Git Tutorial: A Comprehensive Guide by Jenni Choi for Udemy)  

### Notes on Lab 03: Practice with Git
*What did this exercise teach you?*

##### - Add-Commit-Push (ACP) Workflow: To push local changes to GitHub using Terminal (after navigating to the appropriate folder): (1) Save the work; (2) git status; (3) git add; (4) git commit -m "message in 50 characters or fewer reason for this commit"; (5) git push origin main

##### - To pull work down locally from GitHub using Terminal: (*) git pull origin main 

# Notes from Lab:
So you had the brilliant idea of trying to initiate a new project by using Terminal commands like "mkdir" and "touch", so now how do you get all that work that you did in VS Code up on GitHub?

Here's how:

go to projects folder, cd into the folder that you've created

git init  -- to initialize an empty repository (it won't erase your existing files)

git status  -keeping your eye on the ball

git add .  

git status -keeping your eye on the ball
git commit -m "First commit to gitHub from local drive"
git status -keeping your eye on the ball

git push origin main  (this may throw an error about access rights and repo existence, do this:)

gh repo create
Push an existing local repository to GitHub
Path to local repository (just hit enter)
Repository name (the folder you're in)
Description (type in something lovely and brief)
Visibility (make it Public)
Add a remote (yes)
What should the new remote be called (origin)
Would you like to push commits from the current branch to the "origin"? (Yes)

git status -keeping your eye on the ball

If you get "nothing to commit, working tree clean" then you're all set! Woot!

If that didn't work out as expected maybe you can find work it out with this resource: https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github

## *Many, many thanks to Ben for walking me through all this!!!

