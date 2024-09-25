# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test frankenphp https://github.com/theutz/asdf-frankenphp.git "frankenphp -v"
```

Tests are automatically run in GitHub Actions on push and PR.
