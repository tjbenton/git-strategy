# Git Strategies

This project explains git branching strategies, how to use git rebase, organizing your branches, and semantic releases


# Rebase

Rebasing takes your local commits, stores them in a temporary stash, pulls in the latest changes from the remote, then applies the temporary stash at the top of the git history.

The git rebase method is the best way to keep your git history under control and allows you to easily see each PR that has been merged. When a PR is merged it will keep all the commits in the PR together on a single level in the history. 


For the in depth explanation see [REBASE.md](REBASE.md)


<div style="height: 20px"></div>

# Git Branching Strategies

Similar to how the git rebase strategy helps you keep your git history under control. Git branching strategies help you keep your branches under control.

For the in depth explanation see [GIT_BRANCHING_STRATEGIES.md](GIT_BRANCHING_STRATEGIES.md)

<div style="height: 20px"></div>

# Semantic releases

Using annotated commit messages will allow you to easily implement semantic releases for your project.

For the in depth explanation see [SEMANTIC_RELEASES.md](SEMANTIC_RELEASES.md)