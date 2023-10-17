# Git_Essentials_Training
Git Essentials Training provided on LinkedIn

- Create an initial repository on github.com (a user account must be created beforehand).

[Creating a local repository from scratch and adding files a remote repository]
- Run git init to initialize the local repository
git init

- Create an initial file and save it.

- Add the new file to the staging area.
git add first_file.txt

- Commit the file created to the local repository.
git commit -m "Add initial commit."

- Add the files from the local repository to a remote one.
git remote add origin <https://github.com/user/remote_repository.git>

- Push the changes to the remote repository.
git push

- An error returns informing that remote repository has no main branch yet, so another command must be used to set the remote as upstream.
git push --set-upstream origin main



[Cloning an existing repository on github.com]
- Clone the remote repository. This will initialize git locally, create the local repository, and pull all files from the remote repository.
git clone <remote repository path>

- Create a local file. A bash editor like vi, vim, notepad++, etc can be used.
vi example.txt

- Check the status. For beginners, it is wise using this command after each git command to check the following status.
git status

- Populate the file with a simple sentence and save it.
This is an example.

- Add the file to the staging area.
git add example.txt

- Commit the changes to the local repository providing a good message for the action.
commit -m "Add initial file."

- Push the changes to the remote repository.
git push

