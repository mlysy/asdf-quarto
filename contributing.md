# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test quarto https://github.com/mlysy/asdf-quarto.git "quarto --help"
```

Tests are automatically run in GitHub Actions on push and PR.
