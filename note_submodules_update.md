The easiest way of update the directory with submodule, is to execute the following line:

```
git submodule update --remote
```

However, if we would like to keep the track with some other branch, let's call it `stable` as 
in ProGit book, we can make one change in the settings as below:

```
git config -f .gitmodules submodule.ies_subsubmodules.branch stable
```
