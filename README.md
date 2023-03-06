<div align="center">

# asdf-typos [![Build](https://github.com/aschiavon91/asdf-typos/actions/workflows/build.yml/badge.svg)](https://github.com/aschiavon91/asdf-typos/actions/workflows/build.yml) [![Lint](https://github.com/aschiavon91/asdf-typos/actions/workflows/lint.yml/badge.svg)](https://github.com/aschiavon91/asdf-typos/actions/workflows/lint.yml)


[typos](https://github.com/aschiavon91/asdf-typos) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: binaries are needed.

# Install

Plugin:

```shell
asdf plugin add typos https://github.com/aschiavon91/asdf-typos.git
```

typos:

```shell
# Show all installable versions
asdf list-all typos

# Install specific version
asdf install typos latest

# Set a version globally (on your ~/.tool-versions file)
asdf global typos latest

# Now typos commands are available
typos --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/aschiavon91/asdf-typos/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Antonio Schiavon](https://github.com/aschiavon91/)
