# Start Here
This repository is to help our team learn how to use git and github. Here is a link to read more about [git and github](https://docs.github.com/en/get-started/quickstart/about-github-and-git)

## Steps
1. Install git and/or github desktop on your device.
    * [git download](https://git-scm.com/)
    * [github desktop](https://desktop.github.com/)
2. Clone the repository. This makes a copy of the files that you can edit on your machine.
    * [How to clone a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) (there are many different ways to do this)
3. Check if an issue is assigned to you.
4. Create a branch titled something meaningful, like"{Issue Number}-{descriptor of issue}"
    * **Example:** Say I was assigned issue 123 that asked to implement a scroll bar. I could name my branch "123-scroll-bar" to show what I was working on.
    * Sometimes, you will need to work on something that doesn't have an issue opened for it. I recommend opening a new issue that describes what you are planning to work on and name the branch as described above. Otherwise, still try to give a meaningful name to your branch (ex. "automated-tests").
    * Names like "ashley-branch" or "new-stuff" are not helpful to someone reviewing the repository.
5. On your new branch, implement your changes.
6. Commit often. Commit early.
    * [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)
    * [Overview of command line commits](https://github.com/git-guides/git-commit)
    * On github, a commit with two messages will show the first message as a preview and the second message when the commit is clicked. Please make the first message a brief description of the commit and the second message a more detailed description of what was changed
  ![commit](./imgages/example_commit.png)
    * **Example: Command Line Commit** 
          ```
          git commit -m "Changed log file output" -m "Now when unit test fails, the error message {error_msg} is added to the log file. Changes made in files Logger.ts and app.component.ts
          ```
7. Push your changes to remote repository.
    * [git push](https://github.com/git-guides/git-push)
8. Create a pull request to merge changes to master branch.
    * [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
    * [Creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
    * Link pull request with the issue it resolves with "fixes #{issue number}" somewhere in the pull request
    *  **Example:**
  ![pull request example](./images/pull_request.png)
9. Assign someone to review your pull request.
10. Review the pull requests that are assigned to you.
    * Accept merge if changes resolve the issue.
    * Comment on the pull request if more changes are necessary.
11. Resolve merge conflicts.
    * [Resolving conflicts on Github](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)
    * [Resolving conflicts using command line](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)
    * You can also resolve them using your IDE/editor
12. Profit!!!
