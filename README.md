<div align="center">

# asdf-flarectl [![Build](https://github.com/ORCID/asdf-flarectl/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-flarectl/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-flarectl/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-flarectl/actions/workflows/lint.yml)


[flarectl](https://github.com/cloudflare/cloudflare-go) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `gzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add flarectl https://github.com/ORCID/asdf-flarectl.git
```

flarectl:

```shell
# Show all installable versions
asdf list-all flarectl

# Install specific version
asdf install flarectl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global flarectl latest

# Now flarectl commands are available
flarectl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

