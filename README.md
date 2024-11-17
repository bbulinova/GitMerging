# Git merged

## Story

Your friend started a project about listing animal breeds a while ago, but he's having trouble with git. You have decided to give him a hand.

## What are you going to learn?

You will learn:

- Git branching
- resolving merge conflicts
- creating pull requests
- viewing changes
- viewing the history of a repository

## Tasks

1. Create a new branch called `cats`. Add a text file to it called `cat-breeds` with the following content: ``` Persian Siamese Ragdoll Himalayan Snowshoe ``` Merge it into the `master` branch.
    - There's a branch called `cats`, and it contains the requested lines
    - The `cats` branch has been merged into the `master` branch

2. Some prankster has put car brands into the `dog-breeds` file. Create a new branch called `dogs` and replace the five brands with five dog breeds. Add a new car brand to the `dog-breeds` file on the `master` branch. Merge your `dogs` branch into `master` and resolve the merge conflict.
    - There's a branch called `dogs` which contains the `dog-breeds` file containing five dog breeds
    - A new car brand was added to the `dog-breeds` file on the `master` branch before
merging the `dogs` branch into `master`
    - The `dogs` branch has been merged into the `master` branch
    - After resolving the merge conflict the `dog-breeds` file on the `master` branch contains the
same dog breeds as the one on the `dogs` branch

3. There are too few parrot breeds in the `parrot-breeds` file. Create a new branch called `parrots` and add three more parrot breeds to it. Push your branch to the remote `parrots` branch and create a pull request for merging it into the remote `master` branch. Afterwards merge the pull request.
    - There's a branch called `parrots` which contains the `parrot-breeds` file containing five
parrot breeds
    - The `parrots` branch has been pushed to the remote `parrots` branch
    - The pull request for merging the remote `parrots` branch into the remote `master` branch has
been merged.

4. Create a new branch called `breed-changes`. Replace two of the dog breeds in the `dog-breeds` file with two others. Do the same with the `parrot-breeds` file, except for parrots. Don't add or commit yet! View the changes using the `git diff` command. Afterwards add the `dog-breeds` file to the staging area, and check the changes in the staging area.
    - There's a branch called `breed-changes` which has changes to the `dog-breeds` and `parrot-breeds`
files
    - Student has viewed the changes in the repository without adding the files to the staging area
    - Student has viewed the changes in the repository after adding the `dog-breeds` file to the staging
area

5. You have forgotten what changes you made to the `cats` branch. Check out its history! Afterwards check its history including the line changes which happened in each commit.
    - Student has checked out the basic history of the `cats` branch
    - Student has checked out the history of the `cats` branch along with the line changes in files

## General requirements

None

## Hints

- Always make sure that you are on the correct branch when working on an exercise

## Background materials

- <i class="far fa-exclamation"></i> [Step-by-step guide](project/curriculum/materials/pages/guides/git-merged--general.md)
- <i class="far fa-exclamation"></i> [Moving around branches](https://www.atlassian.com/git/tutorials/using-branches/git-checkout)
- <i class="far fa-exclamation"></i> [Branches in a nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
- <i class="far fa-exclamation"></i> [Merge conflicts](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts)
- <i class="far fa-exclamation"></i> [Creating pull requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
- <i class="far fa-exclamation"></i> [Inspecting a repository](https://www.atlassian.com/git/tutorials/inspecting-a-repository)
- <i class="far fa-exclamation"></i> [Comparing changes](https://www.atlassian.com/git/tutorials/saving-changes/git-diff)
- <i class="far fa-book-open"></i> [Why use branches? + branch basics](https://www.atlassian.com/git/tutorials/using-branches)
