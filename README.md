# Vim React Html Snippets

A Vim snippet library for html when creating React components.
This plugin only provides the html(jsx) snippets it works well as a complement
of others snippets like:

https://github.com/epilande/vim-react-snippets

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
" React code snippets
Plug 'cristianoliveira/vim-react-html-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'

" Trigger configuration (Optional)
" let g:UltiSnipsExpandTrigger="<C-l>"
```

## Usage

As any other   -  you use specific codes for autocompletion. For this library
it is basic the html tag name.

#### Skeleton

  - `<> "- Place a custom tag and cursors"`
  - `div "- Place a plain div"`
  - `divc "- Place a div using className"`
  - `div# "- Place a div with ID & className"`
  - `div. "- Place a div with className"`
  - `a "- Place a link and cursor for href"`
  - `img "- Place a img and cursor for src"`
  - `li "- Place a list"`
  - `ol "- Place a ol"`
  - `dl "- Place a dl"`
  - `p "- Place a paragraph"`
  - `select "- Place a Select Box"`
  - `strong "- Place a <strong>"`
  - `table "- Place a HTML <table>"`
  - `span "- Place a <span>"`
  - `span# "- Place a <span> with ID & className"`
  - `span. "- Place a <span> with className"`

### Properties
  - `cn "- Place a className"`
