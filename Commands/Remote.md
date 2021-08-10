# git remote
> When working with git, a **remote** is a any git repository that is not on the machine you're working on.  The counterpart to this is **local**, or the machine that is being developed on. 
>Take GitHub for example, while git is the technology tht allows you to create local repositories, GitHub is the site that will host the remote repositories.  Once stored remotely, you can bring that repository back down or share it with others.
>**Note**: While the repositories (local and remote)are related and track the same project, they can have different states if changes are not shared between the two.
###Adding a remote
>Adding a remote can be added with the `git remote add` command, followed by the name and location of the remote.
>The name is a local name, meaning it's your lable and does not impact the actual remote whatsoever.
```
git remote and origin https://github.com/ElvenfiftyAcademy/GitFundamentals.git
```
### Removing a remote
>A remote can be removed with the `git remote remove` command, followed by the name of the remote.
```
git remote remove origin
```
## Resources
>-[Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[Back to home](.../README.md)