# got push

when you have a [remote](./remote.md) set up youll need to begin to move [commits](./commits.md) to the remote. This can be done using the command 'git push'.

you can attach a name and branch name to your command to specify where youre pushing to.

```

get push origin main
```

this command will push the **main** branch to the remote called **orgin**. this means any commits that are in youre local will be pushed to youre remote.

### Upstream Tracking

Instead of including the name of the remote and the branch youre on evrey time, you can set local branches to track an upstream branch. this means you can tell the branch to push its assigned upstream remote branch by usning the command 'get push'.

```

git push -u origin main
```

after using this command you can use the 'git push' and it will function in the same way.

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

[Back Home](../EWADME.md)


