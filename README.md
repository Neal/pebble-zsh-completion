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

### Installation for oh-my-zsh

1. In the command line, change to `oh-my-zsh` plugins directory:

	```console
	$ cd ~/.oh-my-zsh/custom/plugins
	```

2. Clone the repository into a new directory called `pebble`:

	```console
	git clone https://github.com/Neal/pebble-zsh-completion.git pebble
	```

3. Include `pebble` plugin to your `.zshrc` file along with other plugins:

	```zsh
	...
	plugins=(git pebble)
	...
	```

4. Restart your terminal application.


## Contributors

* [Neal](https://github.com/Neal)

## License

	The MIT License (MIT)

	Copyright (c) 2014 Neal Patel <neal@ineal.me>

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in
	all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
	THE SOFTWARE.
