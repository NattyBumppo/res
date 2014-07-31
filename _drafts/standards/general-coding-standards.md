We enforce these while reviewing code from teammates' commits. It is up to the code reviewer to make any style fixes before signing off on a certain commit. Github allows us to make comments, which will ensure that we can easily communicate about any problems with code styles.

### Code Review
* Nontrivial code should be made on a separate branch and pushed to origin.
* Before merging to master, the merger role should be assigned to whichever teammate seems most appropriate for the particular change.
* Request a code review
 * Push your branch to origin
 * Open an issue (label: code review), assign a reviewer, make any comments
 * Mention branch name & any notable commits on that branch
* A code reviewer will evaluate and comment the code for style, as well as for algorithmic efficiency, comments, and overall structure.
* It is up to a code reviewer to make any changes before merging a branch into master. The changes the code reviewer makes should be discussed with, or at least made known to, the original coder before merging into master.
* A code reviewer will leave any information of interest in a comment of the issue before closing the issue.

### Issue Documentation
* Creating a new issue
 * Each issue should include a full description of what the issue refers to.
 * Bugs should include full repro steps, including OS and browser.
 * Assign the issue to the person who is most likely the most efficient person to resolve an issue, to yourself, or leave it up for grabs.

* Updating an issue
 * If working on a bug fix or new feature, comment with use cases, expected working features, and known problems that are in progress
 * Comment with relevant questions or comments.

* Closing an issue
 * After completing a task, write a comment if needed.
 * Include relevant commit hashes, if applicable

* Duplicate issues
 * Choose one issue to close (usually less conversation or less details in the description)
 * Reference the duplicate issue in the issue to close so they're linked

* Assigning issues
 * If an issue is not assigned to anyone, feel free to grab the issue. Alternatively, assign the issue to someone who is knowledgeable in that area.
 * If an issue is already assigned to someone, do not change the assignment unless there is a mutual agreement.
 * If an issue is assigned to someone, do NOT complete the task/fix the issue without talking to the assignee.
