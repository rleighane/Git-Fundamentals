# git commit
The command `git commit` will take all tracked changes (items added with[get add](./Add.md)) and package them up in what is called a commit.
Commits come with commit messages that are required for eachcommit. You add a message to a commit command by usingthe `-m` flag followed by a messgae in quotes.
A commit messge _can_ be anything, but best practice dicates that you should use that message to indicatethe changes included int he commit.
For example, if we have an applicationwe're working on where we just built out the ability to register new accounts, then you might have some variation of the following:
```
git add.
git commit -m "Added register functionality"
```
The when viewing the history of a gift repository, you can pinpoint where the registration functionality was added.
## Resources
- [Git Commit Documentation](https://git-scm.com/docs/git-commit)
---
[Back to home](../README.md)

