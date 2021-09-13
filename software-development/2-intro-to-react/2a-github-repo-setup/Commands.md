# Common Git Commands

During the course of your development you will need to use certain Git Commands.
This is an abbreviate list of common commands and why you would use them.

## 1. Cloning an Existing GitHub Repo

To clone an existing repository and start working within it you can type the
following. If you omit the new directory name, the directory will be called what
current repository is called. e.g. **https://github.com/{you}/react-app-example**
will become directory **react-app-example**

1. Type **git clone [repository url][new directory name]**

## 2. Creating a Branch

Often you will find yourself needing to fix a bug, create a new widget, feature
etc. A developers first action is typically to create a branch labelled after
the fix action, version, [dev, test, prod], etc. Consult your systems engineer,
product manager for the correct naming convention you organization uses.

1. Type **git branch MyNewBranchName**

## 3. Checkout a Branch

Once you have created a branch or want to switch between branches to perform
work, you need to check it out first. When you checkout a branch it tells the
HEAD (file that monitors changes in your repo) that the current working branch
is said branch. Therefore all work is associated to it.

1. Type **git checkout MyBranchName**

In order to move between branches you must commit your branches first.

## 4. Committing a Branch

During your work session or just because the day has come to an end, you likely
will want to save your work in GitHub with some comments regarding the work
you completed. The following commands will enable you to do this.

1. Type **git add .**

The "." references all changes within the working directory. If you want to be
specific about what commits you're making, enter the following.

1. Type **git add ./file1/directory ./file2/directory**

All or some files have now been added to the local branch stage. To commit a
stage you need to type the following.

2. Type **git commit -m "Some comment regarding the update"**

To finish the commit you need to push it to the repository in GitHub

3. Type **git push**

## 5. Deleting a Branch

If you make a mistake, complete the bug fix, widget, feature add and it has
been merged with another branch you can and should delete this branch to keep
your code base clean. First start by ensuring you're NOT checked out in the
branch you intend to delete. You can observe the checked out branch by following
[Step 6](##6. Listing all Available Branches) below.

1. Type **git branch -d MyBranchName**

## 6. Listing all Available Branches

Often you want to list all available branches for a repository. You have two
options to view available branches: GUI (Browser) or via CMD line.

1. Browser
   1. Navigate to your [GitHub](https://github.com) repository
   1. Select the dropdown on the left typically labelled by default with your **master** or **main** branch.
   1. The branches committed to the repository are listed
2. CMD Line or Terminal
   1. Type **git branch -a**

## Notes

Now there are several different commands that you will likely use over the
lifecycle of a repository however the most commonly used ones are covered
above. For a complete listing of all commands visit the
[Git Documentation](https://git-scm.com/docs)
