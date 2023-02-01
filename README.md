# hoon-stdlib.vim

Vim help file for Hoon Standard Library in disguise of a plugin.

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):
```
Plug 'https://git.sr.ht/~talfus-laddus/hoon-stdlib.vim', { 'branch': 'main' }
```

## Usage

Run the help command with the name:
```
:help ++add
```

## About

The content is based on the [developers.urbit.org repository](https://github.com/urbit/developers.urbit.org/tree/main/content/reference/hoon/stdlib).
The only changes made to the content has been the removal of markdown links.
The syntax has been changed from markdown to Vim helptext (Vimdoc) with [`decipher`](https://git.sr.ht/~talfus-laddus/decipher).

See also [hoon-runes.vim](https://git.sr.ht/~talfus-laddus/hoon-runes.vim)

Reach out to `~talfus-laddus` on Urbit for anything related to this plugin.

## Vimdoc / Vim helpfile Resources

- Essay about Vimdoc: https://github.com/nanotee/vimdoc-notes
- Cheatsheet about helpfiles: https://devhints.io/vim-help
- A linter: https://github.com/machakann/vim-vimhelplint
- And of course: `:help help-writing`
