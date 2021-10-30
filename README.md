# github-example
properly set up repo to easily sync with local version

Create a new repo in github:

New / name the repoository
Make it public
Initialize with a README.md
Click Create button

Clome your repo:

Click github-account/repo-name
Click Code drop down
copy SSH version to clipboard (git@github.com:github-account/repo-name)

Switch back to terminal (Mac)

mkdir  /name of folder to put it
cd to it
git clone <paste copied ssh path>

Push first commit:

Add a file or edit README.md
save
git status - Untracked files  use git add or git add .
git status - green files
git commit -m <message>
git push  or git push origin master 

Check in Github:

file should have been comitted or changed


