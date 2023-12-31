# asdf-dt

[dt](https://dt.plumbing) plugin for [mise](https://github.com/jdx/mise) and [asdf](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Etc](#etc)

# Dependencies

- [curl](https://curl.se)
- [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html)
  - If `pax` is not found, `tar` will be used

# Install

Install this plugin:

```shell
mise plugin add https://github.com/so-dang-cool/asdf-dt.git
# or
asdf plugin add dt https://github.com/booniepepper/asdf-dt.git
```

Use dt (mise):

```shell
mise use dt@latest
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

Check [mise](https://github.com/jdx/mise) or [asdf](https://github.com/asdf-vm/asdf)
readme for more instructions on how to install & manage versions.

# Etc

[BSD 3 Clause](LICENSE)

Upstream project: [dt](https://dt.plumbing)
