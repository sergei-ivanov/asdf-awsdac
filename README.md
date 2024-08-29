<div align="center">

# asdf-awsdac [![Build](https://github.com/sergei-ivanov/asdf-awsdac/actions/workflows/build.yml/badge.svg)](https://github.com/sergei-ivanov/asdf-awsdac/actions/workflows/build.yml) [![Lint](https://github.com/sergei-ivanov/asdf-awsdac/actions/workflows/lint.yml/badge.svg)](https://github.com/sergei-ivanov/asdf-awsdac/actions/workflows/lint.yml)

[AWS diagram-as-code](https://github.com/awslabs/diagram-as-code?tab=readme-ov-file) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add awsdac https://github.com/sergei-ivanov/asdf-awsdac.git
```

AWS diagram-as-code:

```shell
# Show all installable versions
asdf list-all awsdac

# Install specific version
asdf install awsdac latest

# Set a version globally (on your ~/.tool-versions file)
asdf global awsdac latest

# Now awsdac commands are available
awsdac --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sergei-ivanov/asdf-awsdac/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sergey Ivanov](https://github.com/sergei-ivanov/)
