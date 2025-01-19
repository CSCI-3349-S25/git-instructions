# GitHub Classroom Submission Guide

## Using GitHub Desktop (instructions for using git from the command line are below)
1. [Download GitHub Desktop from here.](https://desktop.github.com)
2. Find the installer in your Downloads folder (or wherever things get downloaded on your computer), then double click the installer to install GitHub Desktop. In most cases, this will install the program in your Downloads folder. 
3. Launch GitHub Desktop. When you do this, it might ask you if you want to move it to a more appropriate location (e.g., Applications or Programs). You should agree to this, but remember where it is getting moved to so you can find it easily later! I suggest making a shortcut or alias on your Desktop.
4. Since you have already created a GitHub account, you should now sign in to GitHub.com when prompted, and authorize GitHub Desktop to access your GitHub Files.

5. Once you are all logged in, tou should see a screen like this. Click on the second choice "Clone a Repository from the Internet..."

<img src="img/getstarted.png" width="500">

6. When you select that, you'll see a list of your repositories. All of the labs or problem sets you have accepted invitations to should be visible. Select the repo you want to edit, e.g., `CSCI3349/lab1-yourusername`, where `yourusername` is your GitHub username.

7. Then in the `Local Path` box, change the path to something sensible -- like your Desktop or Documents and then a folder named for the class, as shown in the screenshot below. **Be sure to remember what this location is so you can easily find your files later on!**

<img src="img/selectrepo.png" width="500">

8. Next you'll see a screen like this. If you want to see your local copy of your repo on your computer, you can click on the `Show in Finder` option (which will be something like `Show in File Explorer` in Windows).
 
<img src="img/repoview.png" width="500">

9. On my Mac, when I click on `Show in Finder` this is what I see next: a Finder folder with the same files as I can see on GitHub in my browser! This is your local copy of the repo. This is where you will be doing all the work for whatever lab or problem set you cloned.

<img src="img/classroomlocation.png" width="500">

10. Do you work (e.g., add files, edit files, whatever else I've asked you to do). Make sure when you do the work it shows up the directory for the correct assignment.

<img src="img/updated.png" width="500">

11. Now you are ready to commit your changes from your local copy of the repo on your actual computer to the main copy of the repo on GitHub on the internet!

12. Launch GitHub Desktop. It should look something like this, showing the files that have been added or changed on the left. If you don't see something like this, you should be able to find your current ps1 repo from the drop down menu in the upper left corner.

<img src="img/githubdesktop.png" width="500">

13. Type a message saying what changes you're making in the box that says `Summary (required)`. I typed "adding a slide and screenshot, updating ps1.py".

14. Click `Commit to main`.
15. Then you'll see this screen. Click the blue button that says `Push origin`.

<img src="img/pushorigin.png" width="500">

16. Now you can double check that your changes to the repo on GitHub went through by clicking on `View on GitHub` or just going to github.com in a web browser.

<img src="img/viewongithub.png" width="500">




## Using git from the command line
1. If you aren't sure whether you have `git` installed on your computer, [follow these directions for installing `git` on your computer](https://github.com/git-guides/install-git). You might already have it installed, so be sure to check as described in these instructions.

2. Clone the desired GitHub repo to your own computer. 

* Go to your repo on github.com and click the green Code button, then the copy button.
* Launch a terminal (on Mac: up to the maginfying glass and search for Terminal; on Windows: Start menu `cmd` or `command` or use git bash).
* In the terminal, navigate to where you'd like to keep your repos for this class (e.g., ``cd ~/Desktop/CSCI3349/``).
* Type ```git clone``` and then paste in what you copied, above in the first bullet.

3. Do any work that is required for the problem set and make sure it appears in your repo for the problem set or lab you are working on,

3. Now, in the terminal, navigate in the file system to the folder on your computer where you cloned this repo (e.g., ``cd ~/Desktop/CSCI3349/lab1-yourusername``).

4. The following three commands will submit all your new files and newly edited files:

``git add <filenames>``

``git commit -m "write a comment here about what you did"``

``git push``
