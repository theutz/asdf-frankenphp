<div align="center">

# asdf-frankenphp [![Build](https://github.com/theutz/asdf-frankenphp/actions/workflows/build.yml/badge.svg)](https://github.com/theutz/asdf-frankenphp/actions/workflows/build.yml) [![Lint](https://github.com/theutz/asdf-frankenphp/actions/workflows/lint.yml/badge.svg)](https://github.com/theutz/asdf-frankenphp/actions/workflows/lint.yml)

[frankenphp](https://github.com/theutz/frankenphp) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add frankenphp
# or
asdf plugin add frankenphp https://github.com/theutz/asdf-frankenphp.git
```

frankenphp:

```shell
# Show all installable versions
asdf list-all frankenphp

# Install specific version
asdf install frankenphp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global frankenphp latest

# Now frankenphp commands are available
frankenphp php-cli -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/theutz/asdf-frankenphp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Utz](https://github.com/theutz/)
