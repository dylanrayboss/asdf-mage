<div align="center">

# asdf-mage [![Build](https://github.com/dylanrayboss/asdf-mage/actions/workflows/build.yml/badge.svg)](https://github.com/dylanrayboss/asdf-mage/actions/workflows/build.yml) [![Lint](https://github.com/dylanrayboss/asdf-mage/actions/workflows/lint.yml/badge.svg)](https://github.com/dylanrayboss/asdf-mage/actions/workflows/lint.yml)

[mage](https://magefile.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

This plugin depends on common POSIX utilities (awk, grep, sed, etc.), Bash, Git, and Go. If you have a Go toolchain installed and selected via asdf (asdf current golang), it will be used to retrieve and build mage. Otherwise, asdf will be used to retrieve the latest Go version and that will be used for the build.

# Install

Plugin:

```shell
asdf plugin add mage https://github.com/dylanrayboss/asdf-mage.git
```

mage:

```shell
# Show all installable versions
asdf list-all mage

# Install specific version
asdf install mage latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mage latest

# Now mage commands are available
mage --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dylanrayboss/asdf-mage/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [dylan](https://github.com/dylanrayboss/)
