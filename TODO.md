# X-Team Exercise #2 TODO

This document describes what X-team members must do to complete X-Team Exercise #2.  

## 1. Create a personal GitHub account

All Team Members must complete this step.

  1. Go to GitHub.com
  2. Create a personal account using your wisc.edu email address
  3. Record your GitHub account name and password.
  4. Share your GitHub account name with your X-team members.

## 2. Create a GitHub repository for your team

Only one team member completes this step.

  1. Login to GitHub with your wisc.edu GitHub account
  2. Create a new public repository on that account
  3. Enter name suggested by GitHub for your newly created repository as your repository's name
  4. Enter cs400 X-Team as the description for this new repository
  5. Add Collaborators.  Do the following for each member of your X-team
     a. Click Settings
     b. Click Collaborators
     c. Add each team member's GitHub account name (or wisc.edu email) to the list of members who can edit that repository
  6. Share the name of this repository with all x-team members

## 3. Clone a local copy of this repository

### Create a local clone of this exercise

One student must do this.  Other team members may do this if they wish to edit files from within Linux must complete this step

   1. Login to CS Linux workstation
   2. cd ~/private
   3. mkdir cs400 (if you do not already have this subdirectory)
   4. mkdir cs400/xteam
   5. cd cs400/xteam
   6. git init
   7. git clone https://github.com/cs400-deppeler/super-octo-system   THIS IS OUR REPO (students can't edit)
   
### Copy files from your local repository to your teams repository

One student must do this.  Other team members may do this if they wish to edit files from within Linux must complete this step

   1. git remote add origin https://github.com/<team_members_account>/<xteam's github repository name>   THIS IS YOUR X-TEAM'S REPO
   2. git remote
   3. git push -u origin master  (to copy local files to team's online repository)
   
### To make a change to your team's repository:

Edits may be made online, or from your local repository. These are instructions to make edits from your local repository.
Any team member with a local repository may do this if they wish to edit files from within Linux must complete this step

   1. git pull origin master (to make sure you have latest online commits)
   2. Edit the local file
   3. git add .   (to stage your changes)
   4. git commit -m "describe your changes"
   5. git push origin master   (to upload your edits to your team's GitHub repository so other team members will see them)   

## 4. Learn some markdown and edit a file

All Team Members must complete this step.

  1. Learn a few .md markup rules (https://guides.github.com/features/mastering-markdown/)
  2. Help determine and draft the content for the exercise
  3. Make at least one commit on your team's repository from GitHub
     1. Login to GitHub
     2. Click link to your team's repository
     3. Click link to one of the files.
     4. Click the pencil icon [link] to edit that file.
  6. Make your changes
  7. Describe your changes in the Commit dialog at bottom of page
  8. Commit your edit to your X-team's repository for this project.

We will be able to review the commits to see who has commited each edit to the files.

## 5. Update x_team_rules.md

All team members must help draft content and edit this file.  This file is where you will document the team rules you agree to.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Edit this the rules document so that it establishes some basic rules for your X-team.

## 6. Update x_style_guide.md

This file is where you will document the coding style your team agrees to.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Document your team's opinion or philosophy regarding the value and use of style guides.
3. Edit the Style Guide document so that it describes the Java coding style your team agrees to use for X-Team coding assignments.
4. Document your team's naming conventions and provide examples.
5. Add example comments and a brief statement of your team's commenting style.

## 7. Update your README.md file

1. Replace the title repository name with the name of your repository
2. Answer the questions in the README.md file for your team

## 8. Submit your work

Submit these files to Canvas for your team for this assignment.   The final submission must contain all files.

1. README.md
2. x_team_rules.md
3. x_style_guide.md
  
  
