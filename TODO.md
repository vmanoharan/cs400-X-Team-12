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
  3. Enter name suggested by GitHub for your newly created repository as your repository's name, ie.  your-repo-name
  4. Share the name of this repository with all x-team members
  5. Enter "cs400 X-Team NN" as the description for this new repository.  Replace NN with your X-Team number.
  6. Add Collaborators.  
     a. Click Settings
     b. Click Collaborators
     c. For each member of your X-team
        i. Enter team member's GitHub account name (or wisc.edu email)
        ii. Click Add Collaborator

## 3. Import super-octo-system repository to your team's GitHub repository

Only one team member completes this step.

Note: make the following replacements in the instructions that follow based on the repository made in the previous step:

* replace _github-account-name_ the name of the GitHub account created by your teammate
* replace _team-repo-name_ with the name of the repository that your teammate created

   1. Login to GitHub.
   2. Click link to go to the repository your team's repository.
   3. Click the + in the upper right hand corner of your team's repository page.
   4. Click Import repository.
   5. Type our repo's URL: https://github.com/cs400-deppeler/super-octo-system
   6. Type your team-repo-name in the new 
   7. Specify Public
   8. Review information and click Begin Inport
   9. Wait for import to complete (may take a few minutes)
   
   For more information: https://help.github.com/articles/importing-a-repository-with-github-importer/

## 3.a [optional] Create a local clone of your team's GitHub repository

Any and all team member's may create a local clone.

   1. Login to a CS Linux workstation
   2. cd ~/private
   3. mkdir cs400                         // if you do not already have this subdirectory
   4. mkdir cs400/xteam
   5. cd cs400/xteam
   6. git clone https://github.com/github-account-name/team-repo-name
   8. cd team-repo-name
   9. git remote -v                        // this shows that you are connected to your team's repo      

### 3.b [optiona] Make a change to your team's repository from a local repository:

Any and all team member's may make edits in this way.

   1. Complete step 4.a if you have not
   2. cd ~/private/cs400/xteam/team-repo-name
   3. git pull origin master                       // get all edits from team's GitHub repo
   4. edit the files
   5. git add .
   6. git commit -m "description of your edit"
   7. git push -u origin master                    // put all of your edits into team's GitHub repo

## 4. Learn some markdown and edit a file on GitHub.com

All Team Members must complete this step.

  1. Learn a few .md file markdown rules (https://guides.github.com/features/mastering-markdown/)
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

All team members must help draft content and edit files.  The x_team_rules.md file is where you will document the team rules you agree to.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Edit x_team_rules.md document the agreed upon rules for your X-team.

## 6. Update x_style_guide.md

All team members must help draft content and edit files.  The x_style_guide.md file is where you will document the the coding style rules your team agrees to follow.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Document your team's opinion or philosophy regarding the value and use of style guides.
3. Edit the x_style_guide.md document so that it describes the Java coding style your team agrees to use for X-Team coding assignments.
4. Document your team's naming conventions and provide examples.
5. Add example comments and a brief statement of your team's commenting style.

## 7. Update your README.md file

1. Replace the title (top line of README.md) with the name of your X-team's repository.
2. Answer the questions in the README.md file for your team.

## 8. Submit your work

Submit these files to Canvas for your team for this assignment.   The final submission must contain all files in the same submission.

1. README.md
2. x_team_rules.md
3. x_style_guide.md
  
  
