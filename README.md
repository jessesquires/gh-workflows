# GitHub Workflows

*A collection of useful generic [GitHub Actions workflows](https://docs.github.com/en/actions)*

## About

You can find all workflows in [`.github/workflows/`](https://github.com/jessesquires/gh-workflows/tree/main/.github/workflows).

Each workflow contains comments explaining what it does. Most should be self-explanatory.

Workflows are developed and tested at [jessesquires/sandbox-gh-workflows](https://github.com/jessesquires/sandbox-gh-workflows) to keep this repo history clean.

## Blog Posts

- [Useful label-based GitHub Actions workflows](https://www.jessesquires.com/blog/2021/08/24/useful-label-based-github-actions-workflows/)
- [GitHub Actions workflows for automatic rebasing and merging](https://www.jessesquires.com/blog/2021/10/17/github-actions-workflows-for-automatic-rebasing-and-merging/)
- [Automate merging release branches into your main branch with GitHub Actions](https://www.jessesquires.com/blog/2022/03/26/gh-action-merge-release-to-main/)
- [Running Danger on GitHub Actions](https://www.jessesquires.com/blog/2020/04/10/running-danger-on-github-actions/)
- [Automatically assign milestones with GitHub Actions](https://www.jessesquires.com/blog/2022/08/04/automatically-assign-milestones-with-github-actions/)

## Docs

- [Virtual Environments](https://github.com/actions/virtual-environments/)
- [Documentation](https://docs.github.com/en/actions)

## How to use

1. Add these workflows to your own repo in `.github/workflows/`.
1. Edit workflows as needed.

> 💡 **Note:**
>
> - Some workflows require adding a [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
> - Some workflows expect specific labels to exist, as these are what trigger the workflow. You'll need to create these labels in your repo. If you name the labels differently, you will need to edit the workflow accordingly.
