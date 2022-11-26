# Document your repo in a professional way
![technical-documentation-post-header1](https://user-images.githubusercontent.com/78906545/204106288-5ae3a60d-1bb5-49c3-bc11-cc0d9be5a4de.jpg)

## Learning objectives

- Write descriptive and easy to understand commit messages.
- Write a descriptive and easy to understand README in business English for a submitted project.
- Write short, detailed, and easy to understand descriptions of pull requests.
- Fix mistakes when making commits.
- Communicate technical concepts to non-technical people.
- Communicate technical concepts to other technical people.

### Estimated time: 0.5h

## Description

Apply all of the basic rules in each of your GitHub repositories and remember about the most important rule:  you should always think about the other people that work on your code!

# Professional repo - basic rules

The most important rule in maintaining a professional repo is to always think about people that you share your code with: collaborators, code reviewers, programmers or non-technical users who might want to reuse and/or improve your project.
Ask yourself the question: *what information might they need from you in order to use your repo?*

Also keep them in mind when something unexpected happens. If you realize that you made a mistake and something is not working as it should, communicate it to your collaborators so that they know not to expect the normal behavior from that feature until it is fixed - you can leave a comment, open an issue, or leave a link to the specific line of code.

1. Use descriptive names for your branches (e.g., change-pooling-layer) and make sure that your 'feature branch' is up-to-date with the 'main branch' in your repository.
2. Write a meaningful title for your pull request and always add a short summary of changes introduced in the pull request.
3. Use descriptive commit messages - each commit should be small enough to describe it in one sentence. The commit message should be written in the **imperative tense and capitalized**. [Read more about how to write descriptive commit messages](https://www.freecodecamp.org/news/level-you-up-to-awesome-commit-messages-a85558cb90e8).
4. Do not commit files that are not related to the project.
5. Add descriptive README file to your project - you can use [this template]() but remember to customize it to your project.

## Useful hints

There are a few useful hints that can help you to keep your repo professional:

1. If you need to correct your commit message you can do it for your most recent commit by using [`git commit --amend` command](https://www.atlassian.com/git/tutorials/rewriting-history#git-commit--amend). 
2. If you want to make your GitHub messages more organized you can use [Markdown syntax](https://guides.github.com/features/mastering-markdown/).
3. Remember that adding a file to the `.gitignore` cannot also be used to remove files that you added using that technique. If you committed a useless file into your repo you need to remove it manually.

