<div align="center">

# asdf-protoc-gen-connect-openapi [![Build](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/build.yml/badge.svg)](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/build.yml) [![Lint](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/lint.yml/badge.svg)](https://github.com/eduardopoleoflipp/asdf-protoc-gen-connect-openapi/actions/workflows/lint.yml)

[protoc-gen-connect-openapi](https://github.com/sudorandom/protoc-gen-connect-openapi) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

If you want to contribute and test the scripts you quire having the following utilities

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Adding the plugin:

```shell
asdf plugin add protoc-gen-connect-openapi https://github.com/wishabi/asdf-protoc-gen-connect-openapi
```

Seeing all the available versions
```shell
asdf list all protoc-gen-connect-openapi
```

Installing latest
```shell
asdf install protoc-gen-connect-openapi latest
```

Installing a specific version
```shell
asdf install protoc-gen-connect-openapi 0.17.0
```

# Updating

```shell
asdf plugin update protoc-gen-connect-openapi 
```

# Uninstall

```shell
asdf plugin uninstall protoc-gen-connect-openapi 
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
