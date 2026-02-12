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

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
# asdf plugin add quarto # not supported yet
# or
asdf plugin add quarto https://github.com/mlysy/asdf-quarto.git
```

quarto:

```shell
# Show all installable versions
# uncomment below for asdf version < 0.16.0
# (see https://asdf-vm.com/guide/getting-started-legacy.html)
# asdf list-all quarto
#
# asdf version >= 0.16.0
asdf list all quarto

# Install specific version
asdf install quarto latest

# Set a version globally (on your ~/.tool-versions file)
# uncomment below for asdf version < 0.16.0: 
# asdf global quarto latest
#
# asdf version >= 0.16.0
asdf set -u quarto latest

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
