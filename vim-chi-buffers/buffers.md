# Buffers


## About The Speaker

Josh Branchaud
Work:    Hashrocket
Twitter: @jbrancha
GitHub:  @jbranchaud

Vim Plugins:

- fourohfour.vim
- rails-sql-migrations.vim


## Intro

> No tabs, occasional splits, many buffers

- You will always have many buffers when using Vim

- Splits are great for specific tasks but generally clutter the screen

- Tabs create another dimension of file organization, cognitive overhead


## Hidden

`:h hidden`

`set hidden`


## Buffer List

Open existing and new files

`:h ls`


## Navigating To Buffers

`:h :b[uffer]`

Navigate to a buffer by:

- buffer number (e.g. `:1b` or `:b 1`)
- tab completion of name (e.g. `:b fil<tab>`)

Previous buffer:

`:h Ctrl-^`


## Deleting Buffers

`:h bd[elete]`

`:h bw[ipeout]`


## Buffer List (Revisited)

`:ls!`


## Plugins

Buffer-related plugins that I can't live without

### BufExplorer

`:h bufexplorer`

### BufOnly

`:BO`



## Related Topics

- Execute a command in each buffer (`:h bufdo`)

- Jump List (`:h jumplist`)

- Marks (`:h marks`)
