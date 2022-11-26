# GitHub flow
![image](https://user-images.githubusercontent.com/78906545/204105839-e23903b9-c13b-4057-afa3-ee0e54b28a52.png)


## Learning objectives
- Understand the concept of version control.
- Follow GitHub flow.
- Create branches that each have a different base branch.
- Open PRs in GitHub.

### Estimated time: 1.5h

## What is a version control system? How is it related to Git and GitHub?

A version control system tracks the history of changes to files. It is especially useful in projects built by software development teams.
As the project evolves teams can run tests, fix bugs, and contribute new code with confidence that any version can be recovered at any time.
Reconstructing the edit history of various files can be useful for a variety of reasons, such as when you need to investigate when some change was introduced and why.
You are already familiar with Git and GitHub but it is also important that you understand how they relate to the concept of a version control system.

### What's the difference between Git and GitHub?

**Git** is an example of a distributed version control system. **GitHub** is a Git hosting repository that provides developers with tools to ship better code.
Read the [10 minute long introduction article from the Git Handbook](https://guides.github.com/introduction/git-handbook/) and make sure that you understand this difference.

NOTE: Stop yourself from checking all links in this article!

## GitHub flow

GitHub flow is a detailed process for using branches with your team.

***important note** GitHub flow is slightly different than Gitflow, even though their names look alike.*

### Why is it important?
If everybody in your team uses the same flow, you collaborate more effectively because everyone knows how to track the history of changes in your shared code easily.

### How to use GitHub flow
In order to learn how to use GitHub flow with your team:
- Read this [GitHub Guides article](https://guides.github.com/introduction/flow/) that explains the concept of the GitHub flow with a nice visualization.

## How to use GitHub flow
### Main branch

You can think about the `main` branch as a snapshot of your application that at any moment can be used for:
- deployment to production (which often occurs automatically) - you do not want to deploy broken code by accident.
- developing new features with multiple collaborators - your teammates need a stable version of your project to start implementing changes.

Therefore the `main` branch should always be stable code that actually works and can be safely used. Any changes required in the application should be introduced in `feature` branches and approved before merging them to the `main` branch.

*NOTE: The `main` branch is a rather new name. Previously it was called the `master` branch. GitHub [has changed it for good reasons](https://www.techrepublic.com/article/github-to-replace-master-with-main-starting-in-october-what-developers-need-to-know/), but you can still see some references to the `master` in many articles. Do not let that confuse you.*

### Development branch
Sometimes you want to experiment with a code which you have on your main branch but not want to save it to main branch. In this case, you can create another branch where you can experiment with ease - and if you are satisfied, you can merge the experiment to the main branch later.

### Feature branches

Before you start working on a new feature, you should create a new `feature` branch that is based on the `main` branch. You will use this branch for all your work.

Remember that your branch name should be descriptive (e.g.: `refactor-authentication`, `user-content-cache-key`, `make-retina-avatars`), so that others can see what is being worked on.

### Opening pull requests

Once you start working on any project, initialize its `main` branch. Then, add changes in a `feature` branch(es).
You will need to create a *pull request* to compare your `feature` branch with the `main` branch and send the link to that pull request to your supervisor.
After you send the link to your pull request you will get a code review from your code reviewers. 

You should not merge your pull requests to the `main` branch of your project without a code review that *approves* your changes.

Watch [this 4 min long video](https://www.youtube.com/watch?v=PrIY8sYwe90) with a simple example of GitHub flow and opening a pull request.

