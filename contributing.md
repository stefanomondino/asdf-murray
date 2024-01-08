# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test murray https://github.com/stefanomondino/asdf-murray.git "murray --help"
```

Tests are automatically run in GitHub Actions on push and PR.
