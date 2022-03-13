# Git Hooks

Git hooks are shell scripts run automatically before or after Git executes an important command, such as “Commit” or “Push”.

```shell
git clone https://github.com/pdaambrosio/hooks_validator.git

chmod +x /hooks_validator/hooks/*

git config --global core.hooksPath /hooks_validator/hooks
