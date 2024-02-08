# hoon-stdlib.vim

Vim help file for Hoon Standard Library in disguise of a plugin.

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):
```
Plug 'matthiasschaub/hoon-stdlib.vim', { 'branch': 'main' }
```

## Usage

Run the help command with the name:
```
:help ++add
```

## About

The content is based on the [docs.urbit.org repository](https://github.com/urbit/docs.urbit.org).
The only changes made to the content has been the removal of markdown links.
The syntax has been changed from markdown to Vim helptext (Vimdoc) with [`decipher`](https://github.com/matthiasschaub/decipher).

See also [hoon-runes.vim](https://github.com/matthiasschaub/hoon-runes.vim).

Reach out to `~talfus-laddus` on Urbit for anything related to this plugin.

## Vimdoc / Vim helpfile Resources

- Essay about Vimdoc: https://github.com/nanotee/vimdoc-notes
- Cheatsheet about helpfiles: https://devhints.io/vim-help
- A linter: https://github.com/machakann/vim-vimhelplint
- And of course: `:help help-writing`
