# github-flow-sugar

github-flow 를 좀 더 편하게 써보자

### Installation

#### Using homebrew

1. brew tap bepro-company/brew
2. brew install bepro-company/brew/github-flow-sugar
3. brew upgrade bepro-company/brew/github-flow-sugar

#### Manual install

1. download repository or repository sources.
2. Add or symlink git-* scripts to PATH.

### Usage

#### Create a new branch

```bash
# for DATACENTER-715 Jira ticket
git-feature 715 jira_integration  # DATACENTER is a default project
git-feature DATACENTER-715 jira_integration

# for tickets of RESEARCH, EDITOR projects
git-feature RESEARCH-1 camera_sync
git-feature EDITOR-1 3d_player
```

#### Push commits and make a pull request

```bash
# Jira ticket will be attached in body automatically
git-pr
```
