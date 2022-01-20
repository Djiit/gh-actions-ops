# gh-actions-ops

Random Actions Operations. Use it at your own risk.

## Install

You'll need to have the GitHub CLI installed and be logged against GitHub. On a macOS env, run:

```sh
# Setup GH CLI
brew install gh
gh auth login

# Setup this extension
gh extension install Djiit/gh-actions-ops
```

## Usage

Display some help: 

```sh
gh actions-ops -h
```

Cleanup all runs for a workflow:
```sh
gh actions-ops -wc 123456789
```
