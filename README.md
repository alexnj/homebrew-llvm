# llvm homebrew tap

This is a custom [Homebrew](https://brew.sh/) tap for [llvm](https://github.com/clangd/clangd) based off [the core llvm formula](https://formulae.brew.sh/formula/llvm), built with [remote index support](https://clangd.llvm.org/design/remote-index.html#buildingreleases) (`grpc`). The official `llvm` binary of `clangd` is compiled with `mac+xpc` and does not have remote index support.

## How do I install these formulae?

```shell
brew install alexnj/llvm
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
