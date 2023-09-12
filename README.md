<div align="center">

# pq-provisioner-plugin [![Build](https://github.com/ngyewch/pq-provisioner-plugin/actions/workflows/build.yml/badge.svg)](https://github.com/ngyewch/pq-provisioner-plugin/actions/workflows/build.yml) [![Lint](https://github.com/ngyewch/pq-provisioner-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/ngyewch/pq-provisioner-plugin/actions/workflows/lint.yml)


[pq-provisioner](https://github.com/ngyewch/pq-provisioner) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `unzip`, `git`

# Install

Plugin:

```shell
asdf plugin add pq-provisioner https://github.com/ngyewch/pq-provisioner-plugin.git
```

pq-provisioner:

```shell
# Show all installable versions
asdf list-all pq-provisioner

# Install specific version
asdf install pq-provisioner latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pq-provisioner latest

# Now pq-provisioner commands are available
pq-provisioner version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ngyewch/pq-provisioner-plugin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Ng](https://github.com/ngyewch/)
