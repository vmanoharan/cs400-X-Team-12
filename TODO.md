# X-Team Exercise #2 TODO

This document describes what X-team members must do to complete X-Team Exercise #2.  

## 1. Create a personal GitHub account

All Team Members must complete this step.

  1. Go to GitHub.com
  2. Create a personal account using your wisc.edu email address
  3. Record your GitHub account username and password.
  4. Share your GitHub account username with your X-team members.

## 2. Create a GitHub repository for your team (PLEASE DO NOT FORK THIS REPOSITORY)

Only one team member completes this step.

  1. Login to GitHub with your wisc.edu GitHub account.
  2. Click the green [New Repository] link.
  3. Enter the name suggested by GitHub for your newly created repository as your repository's name, ie.  your-repo-name
  4. Enter "cs400 X-Team NN" as the description for this new repository.  Replace NN with your X-Team number.
  5. Select Public.
  6. Click [Create repository].
  7. Scroll to bottom of Quick Setup page and click [Import Code].
  8. Enter the existing (old) repository's clone URL: https://github.com/cs400-deppeler/super-octo-system
  9. Click [Begin Import] and wait for import to complete.
  10. Click the link to your newly created repository.
  11. Add Collaborators to your newly created repository.  
     a. Click Settings
     b. Click Collaborators
     c. For each member of your X-team
        i. Enter your team member's GitHub account username
        ii. Click Add Collaborator
        
  11. Share the name of this repository with all of your x-team members

## 3. Learn some markdown and edit a file on GitHub.com

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

## 4. Update x_team_rules.md

All team members must help draft content and edit files.  The x_team_rules.md file is where you will document the team rules you agree to.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Edit x_team_rules.md document the agreed upon rules for your X-team.

## 5. Update x_style_guide.md

All team members must help draft content and edit files.  The x_style_guide.md file is where you will document the the coding style rules your team agrees to follow.  Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Document your team's opinion or philosophy regarding the value and use of style guides.
3. Edit the x_style_guide.md document so that it describes the Java coding style your team agrees to use for X-Team coding assignments.
4. Document your team's naming conventions and provide examples.
5. Add example comments and a brief statement of your team's commenting style.

## 6. Update your README.md file

Any team member may complete this step.

1. Replace the title (top line of README.md) with the name of your X-team's repository.
2. Answer the questions in the README.md file for your team.

## 7.a [optional] Create a local clone of your team's GitHub repository

Any and all team member's may create a local clone.

   1. Login to a CS Linux workstation
   2. cd ~/private
   3. mkdir cs400                         // if you do not already have this subdirectory
   4. mkdir cs400/xteam
   5. cd cs400/xteam
   6. git clone https://github.com/github-account-name/team-repo-name
   7. cd team-repo-name
   8. git remote -v                        // this shows that you are connected to your team's repo      

## 7.b [optional] Make and push a change from your local repository to your team's repository:

Any and all team member's may make edits in their local repository and commit to the team repository in this way.

   1. Complete step 7.a if you have not
   2. cd ~/private/cs400/xteam/team-repo-name
   3. git pull origin master                       // get all edits from team's GitHub repo
   4. edit the files
   5. git add .
   6. git commit -m "description of your edit"
   7. git push -u origin master                    // put all of your edits into team's GitHub repo


## 8. Submit your work

Submit these files to Canvas for your team for this assignment.   The final submission must contain all files in the same submission.

1. README.md
2. x_team_rules.md
3. x_style_guide.md
  
  
