# Second-Repositry
This is my second repositry and that time is my learning so that are reason so i created a second repositry 
# if you want to make a folder that see below 
syntax: 
makdir "here your folder name"
# if you want to make a file that see below 
syntax:
touch "Here Your File Name.extension name
Example : touch example.txt

# if you want access the directpries that use cd command 
sytax:
cd "Directories name"

# if you want to clone a repository on your local system so use clone command 
syntax:
git clone "url of your repsitory "

# if you want to commit the file so there are three faces to commit 
# 1. here add file which file that modify or new file so use add command 
syntax:
git add "file name"
IF you want to add all file in one command so you .
syntax:
git add .
# 2. Here commit message put what changes have been made in code so use commit command
Syntax:
git commit -m "Your Message"
# 3. there is last step to push on your file on github account  so use push command 
syntax:
git push origin main   (main is your branch name )

#  If You Want To See The Log Of All Changes So Use This Command 
Syntax:
git log --all --decorate --oneline

#  If You Want To See The Short Log Of All Changes So Use This Command 
Syntax:
git log --short --branches=* --graph

# if you want to add file local to remote so you follow this step
Step 1: Make a file on your local system 
step 2: you use first command 
syntax:
git init
Step 3: Make a repositry on github account 
 Step 4: Go to setting and get the url of your repo
 Step 5: Open terminal and go to your project folder
 Step 6: Now type following command
 syntax :
 git remote add origin "Url of your Repo"
 then verify your  Remote
 syntax:
 git remote -v
 Then final step to push  your file on Github server
 syntax:
 git push -u origin master
 