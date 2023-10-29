<div align="center">

# asdf-dt [![Build](https://github.com/booniepepper/asdf-dt/actions/workflows/build.yml/badge.svg)](https://github.com/booniepepper/asdf-dt/actions/workflows/build.yml) [![Lint](https://github.com/booniepepper/asdf-dt/actions/workflows/lint.yml/badge.svg)](https://github.com/booniepepper/asdf-dt/actions/workflows/lint.yml)

[dt](https://dt.plumbing) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add dt
# or
asdf plugin add dt https://github.com/booniepepper/asdf-dt.git
```

dt:

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

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/booniepepper/asdf-dt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [J.R. Hill](https://github.com/booniepepper/)
