# git_assignment_HeroVired
# Assignment created by Muzahid
# Q1
1. Create a repository name: git_assignment_HeroVired
2. Create a ‘dev’ branch and add this code.
3. Merge this branch with the main branch and make a release of version 1 of the ‘calculator plus app’.
   ```bash
   a. git checkout main
   b. git pull origin main
   c. git merge dev
   d. git commit -m "Merge dev"
   e. git tag -a version1 -m "version1"
   f. git push origin main
   g. git push origin version1
4. Add any of your classmates as collaborators.
5. Implement a feature by creating a new branch called ‘feature/sqrt’. f. Add the ‘sqrt’ code to it.
   ```bash
   a. branch created
   b. git checkout feature/sqrt
   c. git add calculator.py
   d. git commit -m "Initial commit"
   e. git push origin feature/sqrt
6. The bug fixation is in the divide function and the new function should be: def divide(self, a, b)
   ```bash
   a. git add calculator.py
   b. git commit -m "second commit"
   c. git push origin feature/sqrt
8. After completing the feature implementation and ensuring that the application works correctly, create a pull request targeting the main branch.
9. Request a code review from a team member and make any necessary improvements based on the review feedback.
10. Once the code reviewer approves your pull request, merge the "feature/sqrt" branch into the ‘dev’ branch.
11. Finally, do the testing in the ‘dev’ branch itself and merge it into the ‘main’ branch and create a ‘version 2’ release.
    ```bash
    a. git checkout main
    b. git pull origin main
    c. git merge dev
    d. git tag -a version2 -m " Version 2.0"
    e. git push origin version2

**#Q2**

The ubuntu OS of size 263MB is added to LFS file.

#Steps to install Git LFS and push large file to Git
1. Install Git LFS in Windows by downloading from Git LFS website.
2. Initialize Git LFS in the repository.
   ```bash
   git lfs install
3. Add tracking of the type of file which you want to track using LFS.
   ```bash
   git lfs track "*.gz"
4. Commit the .gitattributes files to track which file should be managed by LFS.
   ```bash
   git add .gitattributes
   git commit -m "Add ubuntu os in lfs"
5. Add file to push to github repo
   ```bash
   git add ubuntu-core-22-arm64+raspi.img.xz
6. Commit change to the repository.
   ```bash
    git commit -m "Add ubuntu os in lfs"
7. push change to repository
   ```bash
   git push origin lfs

**#Q3**

1. create a new branch ‘geometry-calculator’
2. Create a new branch named "feature/circle-area" to work on the circle area feature
3. Stash Changes for Circle Area Feature:
   ```bash
   a. git checkout feature/circle-area
   b. git stash
   c. git add .
   d. git status
4. Create a New Branch for Rectangle Area Feature:
5. Stash Changes for Rectangle Area Feature:
   ```bash
   a. git checkout feature/rectangle-area
   b. git stash
   c. git add .
   d. git status
6. Switch Back to Circle Area Branch:
   ```bash
   a. git checkout feature/circle-area
   b. git stash apply
7. Commit and Push Circle Area Feature:
   ```bash
   a. git add area.py
   b. git commit -m "Area of Circle"
   c. git push origin feature/circle-area
8. Switch Back to Rectangle Area Branch:
   ```bash
   a. git checkout feature/rectangle-area
   b. git stash apply
9. Commit and Push Rectangle Area Feature
    ```bash
    a. git add area.py
    b. git commit -m "Area of rectangle"
    c. git push origin feature/rectangle-area
10. Create Pull Requests:
11. Review and Merge
