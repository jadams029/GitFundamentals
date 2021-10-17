# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the maching that is being developed on. 

Take Github for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others. 

**Note**: while the respoitories (local and Remote) are related and track the same project, they can have differnt states if changes are not shared between the two. 

### Adding a remote
A remotes can be added with the `git remote add` commad, followed by the name and location of the remote. 

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever. 

```
git remote add origin https://github.com/ElevenFiftyAcademy/GitFundamentals.git
```
### Removing a remote 

A remotes can be removed with the `git remote remove` command, followed by the name of the remote. 

```
git remote remove origin
```

## Resources 
-[Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)
