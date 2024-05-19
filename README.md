# cpp-github-actions-hello-world

C++ GitHub Actions Hello World

## How to

### Create Repository

[Start](https://github.com/new?template_owner=srz-zumix&template_name=cpp-github-actions-hello-world&owner=%40me&name=cpp-github-actions-hello-world&description=My+clone+repository&visibility=public)

1. Right-click **Start** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.

### Create Workflow

1. Open `Actions` tab.
1. Click `New workflow`.
1. Click `Configure` for `C/C++ with Make` under `Suggested for this repository`.
1. Edit workflow.
   - remove `configure` / `make distcheck` step.
   - Replace `make check` with `make run`.
1. Commit adn PullRequest.
   - Click `Commit Changes..` and a pop-up will appear.
   - Select `Create a new branch for this commit and start a pull request`.
   - Click `Commit Changes`

## Recommend Tutorials

- [skills/hello-github-actions](https://github.com/skills/hello-github-actions)
