# Creating git submodules demo

### Add submodules to this repo:

```git submodule add https://github.com/dhobdensa/submodule-1 submodule-1```

```git submodule add https://github.com/dhobdensa/submodule-2 submodule-2```

.gitmodules should have been generated now

Push the changes to github

---

### Deep clone the project and the submodules

```git clone --recursive https://github.com/dhobdensa/git-submodules-demo.git```

### Keep the parent up to date

When you commit to submodules, the parent will automatically update to reference the latest commit.

Remember to push these parent updates to github 
