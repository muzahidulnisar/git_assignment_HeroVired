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
