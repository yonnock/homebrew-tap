# homebrew-tap

Homebrew formulas for tools by [yonnock](https://github.com/yonnock).

## Usage

```bash
brew tap --custom-remote yungweng/tap https://github.com/yonnock/homebrew-tap
brew install pr-codex-review
```

## Formulas

- [pr-codex-review](https://github.com/yonnock/pr-codex-review): run parallel Codex PR reviews and aggregate them into one GitHub comment.
- [wt](https://github.com/yonnock/wt): create isolated, ready-to-code Git worktrees for GitHub issues, pull requests, and branches.

The logical tap ID stays `yungweng/tap` for both existing and new installations. The explicit remote above points at the renamed GitHub repository. Keep this tap ID in formula dependencies and installation receipts; do not add a second `yonnock/tap` or rewrite receipts for the account rename.
