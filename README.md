<div align="center">

# asdf-quarto [![Build](https://github.com/mlysy/asdf-quarto/actions/workflows/build.yml/badge.svg)](https://github.com/mlysy/asdf-quarto/actions/workflows/build.yml) [![Lint](https://github.com/mlysy/asdf-quarto/actions/workflows/lint.yml/badge.svg)](https://github.com/mlysy/asdf-quarto/actions/workflows/lint.yml)

[quarto](https://quarto.org/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add quarto
# or
asdf plugin add quarto https://github.com/mlysy/asdf-quarto.git
```

quarto:

```shell
# Show all installable versions
asdf list-all quarto

# Install specific version
asdf install quarto latest

# Set a version globally (on your ~/.tool-versions file)
asdf global quarto latest

# Now quarto commands are available
quarto --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mlysy/asdf-quarto/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Martin Lysy](https://github.com/mlysy/)
