# Git-Commands

1. Create a new repository and clone it

git clone repository_url.git


2. Open terminal and go to cloned project directory


3. Add files


4. later use command, git add .


5. git commit -m "comment" 


6. git remote add origin repository_url.git

This may throw a fatal error, enter following command

git remote set-url origin repository_url.git


7. git push origin master

# Add existing project to github

1. Create a new repositiory with the same name as project
2. Open terminal and navigate to project "cd project_name"
3. git init
4. git add .
5. git commit -m "Add existing project files to Git"
6. git remote add origin https://github.com/cameronmcnz/example-website.git
7. git push -u -f origin master
