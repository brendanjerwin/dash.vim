# lemon-dash.vim

This Vim plugin will search for terms using the excellent [Dash.app][Dash]
, making API lookups simple.

It provides a new :Dash family of commands and (recommended) mappings.

[Dash.app][Dash] is a Mac only application. This plugin will enable integration with it via lemonade for cases where your vim is on a remote server, but your terminal is a Mac.

## Commands, Mappings and Configuration

Read the [help][txt-doc] to know more.

## Installation

### Using [Plug][plug]:

Just add this line to your `~/.vimrc` inside plug call:

```vim
Plug 'brendanjerwin/lemon-dash.vim'
```

And run `:PlugInstall` inside Vim or `vim +PlugInstall +qa` from shell.

## License

MIT

## Acknowledgements

I didn't do much. This is a fork-and-tweak from https://github.com/rizzatti/dash.vim

[Dash]: http://kapeli.com/
[txt-doc]: https://raw.githubusercontent.com/brendanjerwin/lemon-dash.vim/master/doc/dash.txt
[plug]: https://github.com/junegunn/vim-plug


