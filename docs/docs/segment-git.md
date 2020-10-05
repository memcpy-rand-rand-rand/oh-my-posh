---
id: git
title: Git
sidebar_label: Git
---

## What

Display `git status` information when in a git repository. Also works for subfolders.
Local changes can also shown by default using the following syntax for both the working and staging area:

- `+` added
- `~` modified
- `-` deleted

## Sample Configuration

```json
{
  "type": "git",
  "style": "powerline",
  "powerline_symbol": "",
  "foreground": "#193549",
  "background": "#ffeb3b",
  "properties": {
    "branch_icon": "",
    "branch_identical_icon": "≡",
    "branch_ahead_icon": "↑",
    "branch_behind_icon": "↓",
    "local_working_icon": "",
    "local_staged_icon": ""
  }
}
```

## Properties

- branch_icon: `string` - the icon to use in front of the git branch name
- branch_identical_icon: `string` - the icon to display when remote and local are identical
- branch_ahead_icon: `string` - the icon to display when the local branch is ahead of its remote
- branch_behind_icon: `string` - the icon to display when the local branch is behind its remote
- local_working_icon: `string` - the icon to display in front of the working area changes
- local_staged_icon: `string` - the icon to display in front of the staged area changes
- display_status: `boolean` - display the local changes or not