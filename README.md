<div align="center">

# asdf-texlive [![Build](https://github.com/javiergarea/asdf-texlive/actions/workflows/build.yml/badge.svg)](https://github.com/javiergarea/asdf-texlive/actions/workflows/build.yml) [![Lint](https://github.com/javiergarea/asdf-texlive/actions/workflows/lint.yml/badge.svg)](https://github.com/javiergarea/asdf-texlive/actions/workflows/lint.yml)

[texlive](https://github.com/javiergarea/asdf-texlive) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add texlive https://github.com/javiergarea/asdf-texlive.git
```

texlive:

```shell
# Show all installable versions
asdf list-all texlive

# Install specific version
asdf install texlive latest

# Set a version globally (on your ~/.tool-versions file)
asdf global texlive latest

# Now texlive commands are available
tex --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome!

[Thanks goes to these contributors](https://github.com/javiergarea/asdf-texlive/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Javier Garea](https://github.com/javiergarea/)
