# git_assignment_HeroVired
# Assignment created by Muzahid
The ubuntu OS of size 263MB is added to LFS file.

#Steps to install Git LFS and push large file to Git
1. Install Git LFS in Windows by downloading from Git LFS website.
2. Initialize Git LFS in the repository.
   ```bash
   #git lfs install
4. Add tracking of the type of file which you want to track using LFS.
   #git lfs track "*.gz"
5. Commit the .gitattributes files to track which file should be managed by LFS.
   #git add .gitattributes
   #git commit -m "Add ubuntu os in lfs"
6. Add file to push to github repo
   #git add ubuntu-core-22-arm64+raspi.img.xz
7. Commit change to the repository.
   #git commit -m "Add ubuntu os in lfs"
8. push change to repository
   #git push origin lfs
