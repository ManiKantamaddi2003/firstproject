### Exercise 1: Version Control Basics

In this exercise, you will practice the basic Git commands related to version control. Follow the instructions below to complete the exercise.

#### Task 1: Initializing a Git Repository

1. Create a new directory called "my-project" on your local machine.
2. Navigate to the "my-project" directory using the command line.
3. Initialize a Git repository in the "my-project" directory using the `git init` command.

#### Task 2: Adding and Committing Changes

1. Create a new file called "index.html" inside the "my-project" directory.
2. Open "index.html" in a text editor and add some HTML content.
3. Use the `git status` command to check the status of your repository. You should see the new file listed as an untracked file.
4. Add the "index.html" file to the staging area using the `git add` command.
5. Run `git status` again to verify that the file has been added to the staging area.
6. Commit the changes with a meaningful commit message using the `git commit` command.

#### Task 3: Viewing the Commit History

1. Use the `git log` command to view the commit history of your repository. You should see the commit you just made, along with its details like commit hash, author, date, and message.

#### Task 4: Creating and Switching Branches

1. Create a new branch called "feature-navbar" using the `git branch` command.
2. Switch to the "feature-navbar" branch using the `git checkout` command.
3. Create a new file called "navbar.html" and add some content to it.
4. Add the "navbar.html" file to the staging area and commit the changes.

#### Task 5: Merging Branches

1. Switch back to the main branch using the `git checkout` command.
2. Merge the changes from the "feature-navbar" branch into the main branch using the `git merge` command.
3. Resolve any merge conflicts if they occur.

#### Task 6: Finalizing the Exercise

1. Use the `git log` command again to view the updated commit history, which should include the merge commit.
2. Verify that both "index.html" and "navbar.html" are present in the repository.
3. Congratulations! You have successfully completed Exercise 1.

By performing these tasks, you will gain hands-on experience with initializing a Git repository, adding and committing changes, viewing the commit history, creating and switching branches, and merging branches.

Continue to the next exercise or refer to the additional resources for more Git practice and advanced topics.
