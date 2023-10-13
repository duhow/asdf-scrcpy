<div align="center">

# asdf-scrcpy [![Build](https://github.com/duhow/asdf-scrcpy/actions/workflows/build.yml/badge.svg)](https://github.com/duhow/asdf-scrcpy/actions/workflows/build.yml) [![Lint](https://github.com/duhow/asdf-scrcpy/actions/workflows/lint.yml/badge.svg)](https://github.com/duhow/asdf-scrcpy/actions/workflows/lint.yml)

[scrcpy](https://github.com/Genymobile/scrcpy) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add scrcpy
# or
asdf plugin add scrcpy https://github.com/duhow/asdf-scrcpy.git
```

scrcpy:

```shell
# Show all installable versions
asdf list-all scrcpy

# Install specific version
asdf install scrcpy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scrcpy latest

# Now scrcpy commands are available
scrcpy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/duhow/asdf-scrcpy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [duhow](https://github.com/duhow/)
