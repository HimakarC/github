#git essentials
#git commands

# To create a branch:
git checkout -b "branch_name"

# To push a branch globally, use:
git remote add repository_name <code_url>

# To merge the branch to main branch
--> Switch to the branch to merge and use:
git merge main_branch

# To apply the changes remotely, use:
git push repository_name branch_name

# To create a file in the repository, use:
--> Create a file and commit the changes and push to the remote(repository).
git push repository_name

# To modify any content
--> Firstly add the file.
--> Commit the changes.
--> Push the changes to remote.
git push repos_name

# To delete a branch globally, use:
git branch --delete branch_name
git push repos_name --delete branch_name

# To delete a file in a branch in github, use:
--> remove the file locally. <br>
--> commit the changes.
--> push the changes remotely.
git rm file_name
git commit -m "message"
git push repos_name file_name
