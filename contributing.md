# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test typos https://github.com/aschiavon91/asdf-typos.git "foo --version"
```

Tests are automatically run in GitHub Actions on push and PR.
