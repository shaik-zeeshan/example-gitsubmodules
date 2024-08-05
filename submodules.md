---
title: Submodules in Git
description: Submodules are a way to include other repositories in a Git repository.
---

# How to create submodules in Git

Submodules are a way to include other repositories in a Git repository. This is useful when you want to include a library or another project in your repository.

To create a submodule, you can use the `git submodule add` command. For example, to add the `lib` repository as a submodule in your project, you can run:

```bash
git submodule add respository_url lib
```

This will add the `lib` repository as a submodule in your project. You can then commit the changes to your repository.

To clone a repository with submodules, you can use the `--recurse-submodules` flag. For example, to clone a repository with submodules, you can run:

```bash
git clone --recurse-submodules repository_url
```

This will clone the repository and its submodules.

To update the submodules in your repository, you can use the `git submodule update` command. For example, to update the submodules in your repository, you can run:

```bash
git submodule update
```

This will update the submodules in your repository.

That's it! You now know how to create and use submodules in Git.
