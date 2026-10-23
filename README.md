# git-helper

An interactive CLI that runs common git workflows for you, so you pick an action from a menu instead of typing the commands.

## Install

```sh
git clone https://github.com/makspavlovskyi/git-helper.git
cd git-helper
npm install
npm install -g .
```

## Use

Run `githelper` inside any git repository, choose an action, then answer its prompts.

| Action | What it does |
|---|---|
| `push` | push all changes |
| `commit_changes` | commit your changes with a message |
| `see_branches` | list all branches |
| `create_branch_switch` | create a branch and switch to it |
| `switch_branch` | switch branches safely |
| `amend_commit` | amend the last commit |
| `undo_soft_commit` | undo the last local commit, keeping the changes |

Built with Node.js, commander and inquirer.
