<div align="center">

# asdf-dt [![Build](https://github.com/booniepepper/asdf-dt/actions/workflows/build.yml/badge.svg)](https://github.com/booniepepper/asdf-dt/actions/workflows/build.yml) [![Lint](https://github.com/booniepepper/asdf-dt/actions/workflows/lint.yml/badge.svg)](https://github.com/booniepepper/asdf-dt/actions/workflows/lint.yml)

[dt](https://dt.plumbing) plugin for [rtx](https://github.com/jdx/rtx) and [asdf](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Install this plugin:

```shell
rtx plugin add https://github.com/so-dang-cool/asdf-dt.git
# or
asdf plugin add dt https://github.com/booniepepper/asdf-dt.git
```

Use dt (rtx):

```shell
rtx use dt@latest
```

Install dt (asdf):

```shell
# Show all installable versions
asdf list-all dt

# Install specific version
asdf install dt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dt latest

# Now dt commands are available
dt --version
```

Check [rtx](https://github.com/jdx/rtx) or [asdf](https://github.com/asdf-vm/asdf)
readme for more instructions on how to install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/so-dang-cool/asdf-dt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [J.R. Hill](https://github.com/booniepepper/)
