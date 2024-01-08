<div align="center">

# asdf-murray [![Build](https://github.com/stefanomondino/asdf-murray/actions/workflows/build.yml/badge.svg)](https://github.com/stefanomondino/asdf-murray/actions/workflows/build.yml) [![Lint](https://github.com/stefanomondino/asdf-murray/actions/workflows/lint.yml/badge.svg)](https://github.com/stefanomondino/asdf-murray/actions/workflows/lint.yml)

[murray](https://github.com/synesthesia-it/murray) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add murray
# or
asdf plugin add murray https://github.com/stefanomondino/asdf-murray.git
```

murray:

```shell
# Show all installable versions
asdf list-all murray

# Install specific version
asdf install murray latest

# Set a version globally (on your ~/.tool-versions file)
asdf global murray latest

# Now murray commands are available
murray --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stefanomondino/asdf-murray/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stefano Mondino](https://github.com/stefanomondino/)
