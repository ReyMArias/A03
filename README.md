Directions on how to use GitHub, GitBash, and WebStorm
1. Signup for GitHub using this link https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home. GitHub will then lead you through the process of creating an account.
2. Download GitBash using this link https://git-scm.com/downloads. Select the download of for your operating system and download GitBash.
3. When GitBash is done downloading, find the download and install GitBash.
4. Return to GitHub. You should be on your page. On the left side, locate the green button with the word 'New' next to an image of a book. Click on that.
5. Name your repository, select if it is public or private, and click the checkbox next to 'Add a README file'. You can also click on the checkbox next to 'Add .gitignore', but it is not needed.
6. Create a local repository by making an empty folder on your pc.
7. Right click, and click on the 'Git Bash here' option. This will open up GitBash with the directory of that folder
8. With GitBash open, type 'git init'. This will initialize the local directory as a Git Repository
9. Create a READEME.md file if you have not done so already, or have not selected the checkbox in step 5.
10. Use command 'git add ." to add all files in your local repository to be commited and pushed to GitHub. Alternatively, you can use 'git add [name of file]' to add specific file
11. Use command 'git commit -m "commit message" to commit the push. Make sure that the message is meaningful and descriptive
12. Use command 'git branch -M main' to connect to your main branch.
13. You will now need either the HTTPS or the SSH of your GitHub repository. You can find it on your repository by clicking the green button that says 'code'. Git hub might also give you the HTTPS or SSH on the repo, as well as a quick start guide.
14. Using the HTTPS or SSH, use command 'git remote add origin [HTTPS or SSH]' to connect to your local and remote repositories.
15. Use command 'git push -u origin main' to push local changes onto your remote repository.
16. Go onto 'https://www.jetbrains.com/community/education/#students' and scroll down to 'apply now'. Enter in relevant information. For the email, make sure to use your school email.
17. If you are renewing your subscription, then check your email for the renewal email, if not, check your email and confirm your subscription.
18. You now have multiple jetbrain programs to chose from. We are using Webstorm so download Webstorm.
19. Install Webstorm. Click next until you are installing Webstorm. Click Finish. Do not import settings
20. In Webstorm, press ctrl+alt+S to open up the system prefferences.
21. On the left, click on 'Version Controls' and then on 'Git'
22. You now need to get the path to your Git executable. Simply search up Git, right click, open path, and then copy the directory. Post that into 'Path to Git Executable'. Click on Test to make sure you have the right path. Path may vary but for me it was D:\NJIT\Spring 2022\IS219\Git\bin\git.exe
23. Now go to Appearance and Behaviors, System Settings, and then Passwords. Add a location for the password file. You might be instructed to add a master password if you select a custom location. Click OK on the bottom
24. On Webstorm, open your repository.
25. Go to file, New, HTML File. name it index and save the file
26. you will be prompted to add the file to Git, click Add.
27. On the top, a few options to the right of File, is a Git option. from here you can commit and push changes. Click on Git, Commit, and then type a commit message, and click on commit
28. You can then click on git again, then push, and your files will be pushed onto Github.

Refferences
- https://njit.instructure.com/courses/21542/files/3171313?module_item_id=688096
- https://njit.instructure.com/courses/21542/files/3171367?module_item_id=688095

Glossary Terms
- **Branch**: A Branch of a repository is an area in a repository with the function of testing out features before commiting them to the main branch, which can be called a trunk
- **Clone**: A clone reffers to creating a copy local copy of a remote repository. This will create a new local repository as well.
- **Commit**: A commit is a change to a file or files, ie you are commiting a change
- **Fetch**: A fetch refferences to creating a copy of a remote repository. This will not affect the local repository.
- **GIT**: a VCS that allows you to manage and keep track of source code histories
- **Github**: A cloud based hosting service for Git repositories
- **Merge**: A merge refferse to the process of putting forked history together. In other words, it combines the differences in files
- **Merge Conflict**: A merge conflict happens during a merge when two different branches edited the same line in a file. In other words, you have different commits on different branches, basically creating two trunks from one branch
- **Push**: A push reffers to uploading local repository files to a remote repository
- **Pull**: A pull reffers to downloading remote repository files to a local repository
- **Remote**: Remote refers to anything not on your pc, ie not local.
- **Repository**: Its the folder that keeps track of all the changes, basically being the history of the project.
