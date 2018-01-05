# Wiki-tutorial
### Wiki Tutorial on GitHub

Wiki and GitDesktop Tutorial.

>This is a line added to the development branch.
>
>New line to merge the development branch into master.

### Merging Changes Through a Pull Request:

1. Switch to the development branch, make some updates to the content in a file, and then save and commit the changes.
2. After committing the changes, click **Push origin** to push your changes to the remote version of the development branch on GitHub.
3. In the GitHub Desktop client, while you have development branch selected, go to **Branch > Create Pull Request**.

	>GitHub opens in the browser with the Pull Request form opened.
	>The left-facing arrow from the development branch towards the master indicates that the pull request (“PR”) wants to merge development into master.

4. Describe the pull request, and then click **Send Pull Request**.

	At this point, engineers would get an email request asking for them to merge in the edits. Play the part of the engineer by confirming the merge request. As long as the merge request doesn’t pose any conflicts, you’ll see a **Merge Pull Request** button.
	
	To see what changes you’re merging into master, you can click the **Files changed** tab. Then click **Merge Pull Request** to merge in the branch, and click **Confirm Merge** to complete the merge.
	
5. Now let’s get the updates you merged into master online into your local copy. In your GitHub Desktop GUI client, select the **master** branch, and then click the **Fetch origin** button. Fetch gets the latest updates from origin but doesn’t update your local working copy with the changes.

	After you click **Fetch origin**, the button changes to **Pull Origin**.

6. Click **Pull Origin** to update your local working copy with the fetched updates.

	Now check your files and notice that the updates that were originally in the development branch now appear in master.

# Pull request workflows through GitHub

By default, your new repository has one branch called “Master.” Usually when you’re making changes or reviews/edits, you create a new branch and make all the changes in the branch. Then when finished, the repo owner merges edits from the branch into the master through a “pull request.”

To make edits in a separate branch on GitHub:

1. Pretend you’re a SME reviewer. Go to the Github repo and create a new branch by selecting the branch drop-down menu and typing a new branch name, such as “sme-review.” Then press your Enter key.

	When you create a new branch, the content from the master (or whatever branch you’re currently viewing) is copied over into the new branch. The branch is like doing a “Save as” with an existing document.

2. Click a file, and then click the pencil icon (“Edit this file”) to edit the file.

3. Make some changes to the content, and then scroll down and click **Commit Changes**. Explain the reason for the changes and commit the changes to your sme review branch by clicking **Commit Changes**.

Reviewers could continue making edits this way until they have finished reviewing all of the documentation. All of the changes are made on a branch, not the master.

## Create a pull request

Now that the review process is complete, it’s time to merge the branch into the master. You merge the branch into the master through a pull request. Any “collaborator” on the team with write access can initiate and complete the pull request. You can add collaborators through Settings > Collaborators.

To create a pull request:

1. View the repository and click the **Pull requests** button on the right.
2. Click the **New pull request** button.
3. Select the branch (“sme review”) that you want to compare against the master.
	
	When you compare the branch against the master, you can see a list of all the changes. You can view the changes through two viewing modes: Unified or Split (these are tabs shown on the right of the content). Unified shows the edits together in the same content area, whereas split shows the two files side by side.
4. Click **Create pull request**.
5. Describe the pull request, and then click **Create pull request**.
