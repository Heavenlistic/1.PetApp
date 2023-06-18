Create a project with file structure on local system.

File structure:

1. Folder 1: Root folder named FleetsApp, contains files and folders
            Subfolders: infra, fleetsmobile and fleetsweb

2. Root folder has files Readme.md, app.txt,a nd a Gitignore file

3. Subfolder infra has files like app.tf, network.tf, security.tf,

4. Subfolder fleetsmobile has a file app.json and

5. subfolder fleetsweb has a file web.js


# Commands in the terminal for main folder path
git init 
(delete all previous .git folders to avoid error)
git add .gitignore 
git status 
git commit -m “Initial push”
    git remote add origin (git link) 
    git branch -M main 
    git push -u origin main
git add .