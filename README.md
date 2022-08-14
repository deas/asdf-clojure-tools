<div align="center">

# asdf-clojure-tools [![Build](https://github.com/deas/asdf-clojure-tools/actions/workflows/build.yml/badge.svg)](https://github.com/deas/asdf-clojure-tools/actions/workflows/build.yml) [![Lint](https://github.com/deas/asdf-clojure-tools/actions/workflows/lint.yml/badge.svg)](https://github.com/deas/asdf-clojure-tools/actions/workflows/lint.yml)


FIXME: [brew-install](https://github.com/clojure/brew-install) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add clojure-tools
# or
asdf plugin add clojure-tools https://github.com/deas/asdf-clojure-tools.git
```

clojure-tools:

```shell
# Show all installable versions
asdf list-all clojure-tools

# Install specific version
asdf install clojure-tools latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clojure-tools latest

# Now clj commands are available
clj --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deas/asdf-clojure-tools/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Steffan](https://github.com/deas/)
