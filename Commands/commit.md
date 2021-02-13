# git commit

The comand 'git commit' will take all tracked changes (items added with[git add](./add.md)) and package them up in whats called a commit.

Commits come with commit messages that are required for each commit. you add a commit command by using the'-m' flag followed by a message in quotes.

A commit message _can_ be anything, but best pratice dictates that you should use that message to indicate the changes included in the commit.

for example, if we have an application we're working on where we just built out the ability to register new account, then you might have some variation of the following:

```

git add .
git commit -m "added register fuctionality"
```

Then when veiewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)