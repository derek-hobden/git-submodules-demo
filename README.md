# Creating git submodules demo

### Add submodules to this repo:

```git submodule add https://github.com/dhobdensa/submodule-1 submodule-1```

```git submodule add https://github.com/dhobdensa/submodule-2 submodule-2```

.gitmodules should have been generated now

Push the changes to github

---

### Deep clone the project AND its submodules

```git clone --recursive https://github.com/dhobdensa/git-submodules-demo.git```

---

### Keep the parent repo up to date

The parent will keep updating its references to all submodules' latest commits.

So remember to push these updates in the parent project to github whenever you update a submodule.
