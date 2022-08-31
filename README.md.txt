## Laboratory 1 [English]

*1. Create a project in Visual Studio and register on github.com*
*2. Create a public repository and enter the terminal*
Windows+R > cmd
*3. Open the root directory*
*4. We check the availability of the repository using git status*
*5. If there is no repository, write*
git init
otherwise, we write 
git config --global user.name Name
git config --global user.email Email
*6. Check that the configurations are saved*
git config -e –global
*7. Add*
git remote add origin repository address
git remote add upstream repository address
*8. After that, write in this root directory (to save the commit locally)*
git add .
git commit -m “first commit”
*9. After that, we need to transfer the commit to the remote*
git push origin master
*10. We make changes to the project in Visual Studio*
*11. We add the changed files to the commit*
// «.» set not to select a separate file, and the system will scan and add all changed files
git add .
git commit -m “second commit”
git push origin master
*12. Next, we create a .gitignore file (we independently find the files that should be in .gitignore for the project in Visual Studio).*
*13. We create a README.md file (file for the description of the repository), in which we add a description of the repository, using markdown markup.*
*14. What is the markdown markup we are using Google Search.*
*15. We again add changes to the commit.*
*16. We are looking for how to create another branch (branch) develop from the master branch and switch to it (using one command).*
*17. Make changes and save in origin develop.*
*18. Then we merge the develop branch with the master branch into master. (git merge).*