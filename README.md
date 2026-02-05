FULL PROCESS: Add Git & Connect Project to GitHub using VS Code
✅ STEP 1: Install Git (only first time)
Check Git installed or not

Open VS Code → open terminal:
Type:
git --version
If version shows → Git installed ✅
If not:

Install Git

Go to: https://git-scm.com

Download Git

Install → Next → Next → Install 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ STEP 2: Open your project in VS Code

Open VS Code
Click File → Open Folder
Select your project folder
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ STEP 3: Initialize Git in project

Open terminal in VS Code:

Ctrl + `


Type:

git init


You will see:

Initialized empty Git repository


Now Git is active in your project.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ STEP 4: Add files to Git

Type:

git add .


This adds all project files.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ STEP 5: Commit files (save snapshot)

Type:

git commit -m "my project upload"


(You can write any message)

If error comes first time:

git config --global user.name "YourName"
git config --global user.email "youremail@gmail.com"


Then again run commit.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ STEP 6: Create repository on GitHub

Open https://github.com

Login

Click + → New repository

Enter repository name (example: pythonlab)

Select Public

❌ Don't add README

Click Create repository
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ STEP 7: Connect VS Code to GitHub repo

After creating repo, copy repo link.

Example:
https://github.com/username/repo.git


Now go to VS Code terminal.

Add GitHub link:
git remote add origin https://github.com/username/repo.git

Set main branch:
git branch -M main
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ STEP 8: Upload project to GitHub

Type:

git push -u origin main


If error comes:

git push -u origin main --force


Login to GitHub if asked.

🎉 DONE

Open GitHub → refresh
Your project will be uploaded.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔁 AFTER THIS (whenever you update code)

Every time you change code:

git add .
git commit -m "update"
git push
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------
Pro VS Code method (1-click way) 
----------------------------------
In VS Code left side:
Click Source Control icon : <img width="54" height="65" alt="image" src="https://github.com/user-attachments/assets/d5460ff3-80b0-4337-823d-1f143e66c587" />


Click Publish to GitHub

Login

Done

