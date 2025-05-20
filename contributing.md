# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test protoc-gen-connect-openapi https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi.git "protoc-gen-connect-openapi --help"
```

Tests are automatically run in GitHub Actions on push and PR.
