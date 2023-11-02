# asdf-dt

[dt](https://dt.plumbing) plugin for [rtx](https://github.com/jdx/rtx) and [asdf](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Etc](#etc)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

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

# Etc

[BSD 3 Clause](LICENSE)

A side quest of [J.R. Hill](https://so.dang.cool)

