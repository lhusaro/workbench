# workbench

A simple brainstorming space, powered by the github frontend, a github action, and a simple python script.

**How it works:**  https://stackoverflow.com/a/72918091/819544  
**What it looks like in action:** https://github.com/dmarx/bench-warmers  

# Setup your own

1. Fork this repository
2. Set "write" access on your `${{ secrets.GITHUB_TOKEN }}`,[instructions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#configuring-the-default-github_token-permissions) here.
3. Change the name of README.stub.template to README.stub
4. Author markdown files

# Rules

1. markdown filenames contain no whitespace
2. the first line (title) starts with a single 'pound' character). 

if you don't like these rules, I welcome PRs ;)
