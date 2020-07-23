---
title: Change a git repo remote url
tags:
  - git/github
emoji: 💻
link:
---

I don't often change the remote url address of my git projects but when I do, I almost always google the process.
Now, I know where to look

```zsh
    git remote set-url <remote-name> <remote-url>
```

Where;

- The `<remote-name>` is the name of the git remote file. e.g `origin`
- The `<remote-url>` is the url to the repo you want to change to. e.g `https://github.com/Preshonyee/preshonyee.git`

Here's how a real scenario would be:

```zsh
git remote set-url origin https://github.com/Preshonyee/preshonyee.git
```
