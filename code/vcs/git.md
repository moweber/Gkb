# Gkb.1
## Git
### ? How to push existing Project to remote --bare repo
**On server:**  
1.`mkdir my_project.git`  
1.`cd my_project.git`  
1.`git --bare init`  
**On client:**  
1.`mkdir my_project`  
1.`cd my_project`  
1.`touch .gitignore`  
1.`git init`  
1.`git add .`  
1.`git commit -m "Initial commit"`  
1.`git remote add origin youruser@yourserver.com:/path/to/my_project.git`  
1.`git push origin master`

### ? How do you do this on various IDEs...
**Android Studio:**
