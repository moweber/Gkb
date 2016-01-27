# Gkb.1
## Git
### ? How to push existing Project to remote --bare repo
~~~On server:  
`mkdir my_project.git`  
`cd my_project.git`  
`git --bare init`  
On client:  
`mkdir my_project`  
`cd my_project`  
`touch .gitignore`  
`git init`  
`git add .`  
`git commit -m "Initial commit"`  
`git remote add origin youruser@yourserver.com:/path/to/my_project.git`  
`git push origin master`
~~~
### ? How do you do this on various IDEs...
**Android Studio:**
