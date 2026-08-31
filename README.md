# zed-x

X language support for the [Zed](https://zed.dev) editor. Registers the
[tree-sitter-x](https://github.com/afrigon/tree-sitter-x) grammar and language
configuration so `.x` files get syntax highlighting, bracket and quote
autoclosing, and `//` comment toggling.

## Install

```sh
git clone git@github.com:afrigon/zed-x.git
```

In Zed, run `zed: install dev extension` from the command palette and select
the cloned directory. Zed compiles the grammar and loads the extension.
