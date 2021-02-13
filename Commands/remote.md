# git remote

When working with git, a **remote** is any git repository that is not on the machine your working on. the counterpart to this is **local**, or the machine that is being developed on.

take GitHub for example. WHile git is the technology that allows you to create local repositories, Git Hub is the site that will host your local repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a Remote

A remote can be added with the 'git remote add' command, followed by the name and location of the remote.

The name is a local name, meaning its your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/elevenfiftyacademy/Gitfundamentals.git
```

### Removing a Remote

a remote can be removed with the 'git remote remove' command, followed by the name of the remote.

```

git remote remove origin
```

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to Home](../README.md)