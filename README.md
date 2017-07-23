# Vim React Html Snippets

A Vim   -  library for React in ES6. This plugin only provides the html(jsx)
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

As any other   -  you use specific codes for autocompletion. For this library
it is basic the html tag name.

#### Skeleton

  - `<> "place a open tag and closed with multiple cursors"`
  - `div "Plain div"`
  - `divc "Place a div using className"`
  - `div# "<div> with ID & className"`
  - `div. "<div> with className"`
  - `a "Link"`
  - `address "<address>"`
  - `b "<b>"`
  - `button "<button>"`
  - `img "place a <img>"`
  - `li "place a list"`
  - `ol "place a <ol>"`
  - `dl "place a <dl>"`
  - `p "paragraph"`
  - `select "Select Box"`
  - `strong "<strong>"`
  - `table "HTML <table>"`
  - `span "<span>"`
  - `span# "<span> with ID & className"`
  - `span. "<span> with className"`
  - `cn "<span> with className"`
  - `cn "place a className"`
