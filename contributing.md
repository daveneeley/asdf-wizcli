# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test wizcli https://github.com/daveneeley/asdf-wizcli.git "wizcli --help"
```

Tests are automatically run in GitHub Actions on push and PR.
