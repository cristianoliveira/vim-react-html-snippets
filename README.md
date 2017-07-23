# Vim React Html Snippets

A Vim snippet library for React in ES6. This plugin only provides the html(jsx)
snippets if you are searching for snippets when creating the react components
structures take a look in this project:

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

As any other snippet you use specific codes for autocompletion. For this library
it is basic the html tag name.

#### Skeleton

snippet <> "place a open tag and closed with multiple cursors" w
snippet div "Plain div" b
snippet divc "Place a div using className" b
snippet div# "<div> with ID & className" w
snippet div. "<div> with className" w
snippet a "Link" w
snippet address "<address>" w
snippet b "<b>" w
snippet button "<button>"
snippet img "place a <img>"
snippet li "place a list" w
snippet ol "place a <ol>"
snippet dl "place a <dl>"
snippet p "paragraph" w
snippet select "Select Box" w
snippet strong "<strong>" w
snippet table "HTML <table>" w
snippet span "<span>" w
snippet span# "<span> with ID & className" w
snippet span. "<span> with className" w
snippet cn "<span> with className" w
snippet cn "place a className" w
