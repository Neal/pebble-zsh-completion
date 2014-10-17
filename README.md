# pebble-zsh-completion

A [zsh](http://www.zsh.org) completion script for [pebble](https://developer.getpebble.com/2/additional/pebble-tool/).

## Installation

Drop the `_pebble` file into a directory on your `fpath`.

```sh
$ cp _pebble /usr/local/share/zsh/site-functions/
$ exec zsh
```

To list all the directories on your `fpath`:

```sh
$ echo "$fpath" | tr " " "\n"
```

## Contributors

* [Neal](https://github.com/Neal)
