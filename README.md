<div align="center">

# asdf-protoc-gen-connect-openapi [![Build](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/build.yml/badge.svg)](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/build.yml) [![Lint](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/lint.yml/badge.svg)](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/lint.yml)

[protoc-gen-connect-openapi](https://github.com/sudorandom/protoc-gen-connect-openapi) plugin for the [asdf version manager](https://asdf-vm.com). Ideally, this plugin should be hosted along side the actual project but the maintainer has not got back to us regarding that issue

</div>

# Dependencies

If you want to contribute and test the scripts you quire having the following utilities

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Adding the plugin:

```shell
asdf plugin add protoc-gen-connect-openapi https://github.com/wishabi/asdf-protoc-gen-connect-openapi
```

# Updating

```shell
asdf plugin update protoc-gen-connect-openapi 
```

# Uninstall the plugin

```shell
asdf plugin uninstall protoc-gen-connect-openapi 
```

protoc-gen-connect-openapi:

```shell
# Show all installable versions
asdf list all protoc-gen-connect-openapi

# Install latest version
asdf install protoc-gen-connect-openapi latest

# Install a specific version
asdf install protoc-gen-connect-openapi 0.17.0
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
