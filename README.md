# Wiki-tutorial
### Wiki Tutorial on GitHub

Wiki and GitDesktop Tutorial.

>This is a line added to the development branch.

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

