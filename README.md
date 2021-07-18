<div align="center">

# asdf-age [![Build](https://github.com/adongy/asdf-age/actions/workflows/build.yml/badge.svg)](https://github.com/adongy/asdf-age/actions/workflows/build.yml) [![Lint](https://github.com/adongy/asdf-age/actions/workflows/lint.yml/badge.svg)](https://github.com/adongy/asdf-age/actions/workflows/lint.yml)


[age](https://htmlpreview.github.io/?https://github.com/FiloSottile/age/blob/master/doc/age.1.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add age
# or
asdf plugin add age https://github.com/adongy/asdf-age.git
```

age:

```shell
# Show all installable versions
asdf list-all age

# Install specific version
asdf install age latest

# Set a version globally (on your ~/.tool-versions file)
asdf global age latest

# Now age commands are available
age --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/adongy/asdf-age/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Anthony Dong](https://github.com/adongy/)
