# Instructions for navigating the repository

## Forking
Go to the repository you want to fork, which in this case is "https://github.com/learn-co-curriculum/dsc-phase-1-project.git"
On the top right corner, click on  **Fork** 
This will direct you a new page where to can create a copy to your personal account, name your repository folder and deselect copy the master branch only. Enter create fork

## Cloning
### Step 1:
Open up your command prompt (Windows)/ terminal (Mac)
### Step 2
**mkdir Project-Phase-1** Creating a folder to a specific location in your computer
### Step 3
**cd Project-Phase-1** This will go inside your folder
### Step 4
**git remote -v** This is to see what is inside of your folder currently have and if is also already cloned repo. if there is an existing remote origin (when you trying to push and receive an error: failied to push some refs to "http...", means its have an existing remote origin) use **git remote origin**
### Step 5:
If cloning a branch enter the specific name of the branch and follow by a git code. In this case, **git clone -b template-mvp https://github.com/learn-co-curriculum.dsc-project-template.git** (It is now cloned into your computer) 
### Step 6:
**cd dsc-phase-1-project** This will go inside your folder
### Step 7:
**git https://github.com/learn-co-curriculum/dsc-phase-1-project.git** Add to your repository if have existing then got to step 4 to remove
### Step 8:
**git remote -v** To check what your URL is diplaying
## Pushing
### Step 9:
If changes were made in jupyter notebook and you want to update your repositiory. Type in **git add .**
### Step 10:
**git status** this will show what of what you have changed
### Step 11:
**git commit -m "first push"** You are commited to your changes. In the quotation mark, you can put any message
### Step 12:
**git branch -M main** you can create a new branch with your notes
### Step 13:
**git push -u origin main** 
### Step 14:
If you want to update anymore changes, you can repeat step 9.
