<div align="center">

# asdf-bingo [![Build](https://github.com/isindir/asdf-bingo/actions/workflows/build.yml/badge.svg)](https://github.com/isindir/asdf-bingo/actions/workflows/build.yml) [![Lint](https://github.com/isindir/asdf-bingo/actions/workflows/lint.yml/badge.svg)](https://github.com/isindir/asdf-bingo/actions/workflows/lint.yml)

[bingo](https://github.com/bwplotka/bingo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `go`, `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add bingo
# or
asdf plugin add bingo https://github.com/isindir/asdf-bingo.git
```

bingo:

```shell
# Show all installable versions
asdf list-all bingo

# Install specific version
asdf install bingo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bingo latest

# Now bingo commands are available
bingo version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
