<div align="center">

# asdf-clj [![Build](https://github.com/deas/asdf-clj/actions/workflows/build.yml/badge.svg)](https://github.com/deas/asdf-clj/actions/workflows/build.yml) [![Lint](https://github.com/deas/asdf-clj/actions/workflows/lint.yml/badge.svg)](https://github.com/deas/asdf-clj/actions/workflows/lint.yml)


[clj](https://github.com/clojure/brew-install) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add clj
# or
asdf plugin add clj https://github.com/deas/asdf-clj.git
```

clj:

```shell
# Show all installable versions
asdf list-all clj

# Install specific version
asdf install clj latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clj latest

# Now clj commands are available
clj --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deas/asdf-clj/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Steffan](https://github.com/deas/)
