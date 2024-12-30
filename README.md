<div align="center">

# asdf-oco [![Build](https://github.com/dmayo2/asdf-oco/actions/workflows/build.yml/badge.svg)](https://github.com/dmayo2/asdf-oco/actions/workflows/build.yml) [![Lint](https://github.com/dmayo2/asdf-oco/actions/workflows/lint.yml/badge.svg)](https://github.com/dmayo2/asdf-oco/actions/workflows/lint.yml)

[oco](https://github.com/dmayo2/oco) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add oco
# or
asdf plugin add oco https://github.com/dmayo2/asdf-oco.git
```

oco:

```shell
# Show all installable versions
asdf list-all oco

# Install specific version
asdf install oco latest

# Set a version globally (on your ~/.tool-versions file)
asdf global oco latest

# Now oco commands are available
oco
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dmayo2/asdf-oco/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dobb](https://github.com/dmayo2/)
