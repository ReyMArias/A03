Directions on how to use GitHub

Step 1: Signup for GitHub using this link https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home. GitHub will then lead you through the process of creating an account.
Step 2: Download GitBash using this link https://git-scm.com/downloads. Select the download of for your operating system and download GitBash.
Step 3: When GitBash is done downloading, find the download and install GitBash.
Step 4: Return to GitHub. You should be on your page. On the left side, locate the green button with the word 'New' next to an image of a book. Click on that.
Step 5: Name your repository, select if it is public or private, and click the checkbox next to 'Add a README file'. You can also click on the checkbox next to 'Add .gitignore', but it is not needed.
Step 6: Create a local repository by making an empty folder on your pc.
Step 7: Right click, and click on the 'Git Bash here' option. This will open up GitBash with the directory of that folder.
Step 8: With GitBash open, type 'git init -b main'. This will initialize the local directory as a Git Repository
Step 9: Use command 'git add .' to add all files inside the repository for the first commit. There should be no files at the moment. 
Step 10: Go to GitHub and grab either the HTTPS or the SSH for your repository. These are located on the green 'code' button when you look at your repository.
Step 11: Use command 'git remote add origin [the HTTPS or the SSH]'. You should not be connected to your remote repository. You can check to see which remote you are in by using the command 'git remote -v'
Step 11: Use command 'git push origin main'. This pushes any changes done on your local repository to your remote repository. You can use 'git pull origin main' to pull any changes on your remote repository to your local repository.


