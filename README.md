experiment-4:
------------

Configure the web application and Version control using Git using Git commands and version control
operations. 
=====================================================================================================


Grade Generator Web Application
Overview
The Grade Generator Web Application is a simple web-based tool designed to calculate and display the total and average marks of a student in three programming subjects: Java, Python, and C. The application features an HTML form where users can input their marks, and it provides options to calculate both the total and average marks.

Features
Input fields for student name and marks in Java, Python, and C.
Buttons to calculate the total and average marks.
Display areas for showing the calculated total or average.
Getting Started
Prerequisites
Make sure you have the following installed on your machine:

A modern web browser (e.g., Chrome, Firefox)
A code editor (e.g., VSCode, Sublime Text) for viewing/editing files
File Structure
The project consists of three main files:

index.html: The main HTML file that structures the web page.
style.css: The CSS file that styles the web page.
script.js: The JavaScript file that adds interactivity to the web page.
Project Setup
Clone the Repository

If the project is hosted on a platform like GitHub, clone the repository to your local machine:

bash
Copy code
git clone https://github.com/username/repository.git
Navigate to the Project Directory

bash
Copy code
cd repository
Open the Project

Open the index.html file in your preferred web browser to view the application. Alternatively, you can use a local development server for a better development experience.

Usage
Open the Web Application

Open index.html in your web browser.

Enter Data

Enter the student's name.
Input marks for Java, Python, and C in the respective fields.
Calculate

Click the "Total" button to calculate the total marks.
Click the "Average" button to calculate the average marks.
View Results

The results will be displayed below the buttons:
Total: Displays the total marks obtained in all three subjects.
Average: Displays the average marks calculated from the total.
Code Explanation
HTML (index.html)
Defines the structure of the web page, including input fields for student marks, buttons for calculating totals and averages, and display areas for results.

If you want to contribute to this project, follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your changes to your forked repository.

1. git init
Description: Initializes a new Git repository in the current directory. This creates a .git directory that will hold all of Git’s metadata and version history.

Usage:

bash

git init
Example: Initialize a new repository in a project folder.

bash

cd my-project
git init

----------------------------------------------------------------------------
2. git clone
Description: Creates a copy of an existing remote repository on your local machine. This command clones the entire repository including its history.

Usage:

bash

git clone [url]
Example: Clone a repository from GitHub.

bash

git clone https://github.com/username/repository.git
-------------------------------------------------------------------------------------------------------------------------------------------
3. git status
Description: Shows the status of your working directory and staging area. It lists which files are staged for the next commit, which files have changes, and which files are untracked.

Usage:

bash

git status
Example: Check the current status of your working directory.

bash

git status
---------------------------------------------------------------------------------------------------------------------------
4. git add
Description: Stages changes (new or modified files) for the next commit. This command adds files to the staging area, preparing them for a commit.

Usage:

bash

git add [file]
Examples:

Stage a specific file:
bash

git add index.html
Stage all changes in the current directory:
bash

git add .
-------------------------------------------------------------------------------------------------------------------------------------------
5. git commit
Description: Records the changes made to the repository. A commit is like a snapshot of your project at a given point in time. You must provide a commit message that describes the changes.

Usage:

bash

git commit -m "Commit message"
Example: Commit changes with a message.

bash

git commit -m "Fix bug in login function"
---------------------------------------------------------------------------------------------------------------------------------------------
6. git log
Description: Displays the commit history of the repository. You can see a list of commits with their unique IDs, authors, dates, and commit messages.

Usage:

bash

git log
Example: View the commit history.

bash

git log
--------------------------------------------------------------------------------------------------------------------------------
7. git diff
Description: Shows the differences between the working directory and the staging area, or between two commits. This helps you see what changes have been made.

Usage:

bash

git diff
Example: View changes in the working directory that are not yet staged.

bash

git diff
----------------------------------------------------------------------------------------------------------------
8. git branch
Description: Lists all branches in your repository. You can also create or delete branches with this command.

Usage:

bash

git branch
Examples:

List all branches:
bash

git branch
Create a new branch:
bash

git branch new-feature
-------------------------------------------------------------------------------------------------------------------------------------------------------
9. git checkout
Description: Switches to a different branch or restores files to a previous state. It updates the working directory to match the specified branch or commit.

Usage:

bash

git checkout [branch-name]
Examples:

Switch to an existing branch:
bash

git checkout main
Create and switch to a new branch:
bash

git checkout -b new-feature
------------------------------------------------------------------------------------------------------------------------------------------------
10. git merge
Description: Merges changes from one branch into another. It combines the history of two branches.

Usage:

bash

git merge [branch-name]
Example: Merge changes from the feature branch into the main branch.

bash

git checkout main
git merge feature
--------------------------------------------------------------------------------------------------------------------------------------------------------------
11. git pull
Description: Fetches changes from a remote repository and merges them into the current branch. This command is used to update your local repository with changes from others.

Usage:

bash

git pull [remote-name] [branch-name]
Example: Pull changes from the main branch of the origin remote.

bash

git pull origin main
------------------------------------------------------------------------------------------------------------------------------------------------------------------
12. git push
Description: Uploads local commits to a remote repository. This command is used to share your changes with others.

Usage:

bash

git push [remote-name] [branch-name]
Example: Push changes to the main branch of the origin remote.

bash

git push origin main
-------------------------------------------------------------------------------------------------------------------------------------------------------
13. git reset
Description: Undoes changes by moving the current branch to a specified commit. It can be used to unstage changes or to remove commits.

Usage:

bash

git reset [commit-id]
Examples:

Unstage a file:
bash

git reset [file]
Hard reset to a specific commit (discard changes):
bash

git reset --hard [commit-id]
-------------------------------------------------------------------------------------------------------------------------------------------------------------
14. git rm
Description: Removes files from the working directory and stages the removal for the next commit.

Usage:

bash
Copy code
git rm [file]
Example: Remove a file and stage the removal.

bash

git rm obsolete-file.txt
-----------------------------------------------------------------------------------------------------------------------------------------------------------
15. git tag
Description: Creates a tag (a named reference to a specific commit) that can be used for marking releases or important points in the history.

Usage:

bash

git tag [tag-name]
Examples:

Create a tag:
bash

git tag v1.0
Push tags to a remote:
bash

git push origin v1.0
