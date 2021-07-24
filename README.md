<div align="center">

# asdf-swaks [![Build](https://github.com/nklmilojevic/asdf-swaks/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-swaks/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-swaks/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-swaks/actions/workflows/lint.yml)


[swaks](https://github.com/junegunn/swaks) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add swaks
# or
asdf plugin add swaks https://github.com/nklmilojevic/asdf-swaks.git
```

swaks:

```shell
# Show all installable versions
asdf list-all swaks

# Install specific version
asdf install swaks latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swaks latest

# Now swaks commands are available
swaks --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-swaks/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
