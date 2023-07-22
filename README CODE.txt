GITHUB and GIT

Gitgub--- a repository
git- it is an open version control system..maintains a version (current,next)... able to do multiple task in the repository

-We need a central repository where we can commit the code
-
README.md

echo "# GitPractice" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Radjora5/GitPractice.git
git push -u origin main


   
 rm means remove
 git remote -v....it can show that you are not connected/repository you are linked at
 git remote rm origin.......disconnect from origin...unlink
 Init..Initializing empty gt repository
 README  is a file
 README.md U-- u means Untracked
 A--Added
 git add--- adding a file
 git status to check the file
 git rm --cached README.md.... will remove the file so it will be untracted  README.me  U
 git commit ---- send the file to be commited in the repository
 
 git config --global user.email "bellorama4@gmail.com"
 git config --global user.name "Rama Bello"
 
 git branch is master branch but we name to rename it to the main branch