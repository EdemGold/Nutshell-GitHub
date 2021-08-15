Many developers who don’t follow a particular workflow say that it’s a waste of time and that it takes away precious development time. There is a truth in that statement, because following the workflow means waiting for other people to review your code. Even so, you have to keep in mind that you don’t have to wait around doing nothing. While you wait for a review, you can directly go on to solve another issue! That’s why branches are so powerful in Version Control Systems; you can work on multiple issues at the same time.

With the workflow, you can begin to work on an issue, ask for some ideas or directive from your peers, and then work on another issue while you await responses. After you receive the necessary feedback, you can continue to work on the first issue.  You may repeat this until the issue is resolved.

Pull Requests, as useful as they are, are a fairly easy-to-understand concept. Submitting a Pull Request, or PR, is just asking for permission to apply all the commits in a branch to another branch. All the same, we’re moving too fast. Before learning about Pull Requests, we have to learn what a “pull” is.

Pull
In Git terminology, a pull is just the opposite of push (give yourself a high five if you guessed that!). Push takes your branch and copies all its commits to a remote branch. It also creates the branch if it doesn’t exist on the server yet. Pull is just that, but backward; it looks at a remote branch and copies the commits on it to your local repository. It’s just an exchange of commits; push if it’s from local to remote, and pull if it’s from remote to local.

The syntax is very similar too:

git pull <remote_name> <branch_name>

For example, if you wanted to get the commits from the master branch on GitHub, you would have to execute the command while checking out the master branch:

 git pull origin master

In the last example, there is a new call to action on the page, right above the list of branches. It shows the name of the branch that you just created, and a big button for creating a PR. Click the button to continue; you should get to the Pull Request creation form, just like the Figure below;


You can note that the PR creation form is very similar to the issue creation form.

On the right, you can find the same information about assignees and labels; they work exactly the same. On the bottom of the page, you can see the commits to be applied by the Pull Request; and if you scroll down, you’ll find the differences between the versions.

Check Figure below for an example of this.


After you create a Pull request, the reviewer can then review the changes. After the review, if the changes are great,  the branch will be merged with the master branch.

Git Merge
The changes made to the data-preprocessing will only be on the branch until we merge the branch with the master branch. To merge the two branches, we use the git merge command,

To do that, run the command below;

Git status to check the status of the repository. As shown in the figure below, we are still in the data-preprocessing branch

2. Run git log to check the project history. 


As shown in the figure below, we are on branch data-preprocessing and the branch has one commit.

Use the option “--oneline” when using git log to get a prettier result.

3. As you can see in the figure above, HEAD now points to the last commit of our new branch; which means that every commit we create will have that as a parent. You will also notice that the master didn’t change; that’s because we only worked on our newly created branch. Now that we are satisfied with our fix, let’s merge the branch to the master branch so we can test it. To merge our branch into master, we have to first check it out. Hence, switch to the master branch by running  the git checkout command.

4. Now let’s try to merge the branch into the master branch. Merging just means reproducing all the commits on one branch on another. To do so, we will use the “git merge” command, followed by the name of the branch being merged.

 git merge <name>

Since we are looking to merge “data-preprocessing” into “master,” ourcommand to execute on the master branch is;

git merge data-preprocessing


Let's check the history of the repository by running the “git log” command;

As you can see, “HEAD“ now points to “develop” because it’s the checked-out branch. You can also notice that master  and data-preprocessing  now point to the same commit; that’s because of the merge.

The changes made now are only on the local repository. Therefore, to push the changes to the remote repository, we use the git push command.

git push


Now, check the remote repository to see if the changes reflected on it. It should look like this;