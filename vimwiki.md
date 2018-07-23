# Vimwiki stuff

## Tasks

You can create a new task with `C-space`. `gl<space>` and `gL<space>` will
remove checkboxes.

`C-T` and `C-D` changes the level of lists when in insert mode

`gl` plus a list symbol will change the list to that symbol

Playground:

- [X] Stuff
- [ ] Things
  * [ ] More Things
  * [ ] Foo
  * [ ] Bar
  * [ ] Baz

## Equations

You can create latex equations by enclosing the equation in `$$`

 $ \sum_i a_i^2 = 1 $

## Tables

Start table with `VimwikiTable`

| a | b | c | d | e |
|---|---|---|---|---|
|   |   |   |   |   |

## Exporting with pandoc

vimwiki can export as html but to export to pdf I use pandoc:

```
pandoc index.md --pdf-engine=xelatex -o notes.pdf
```

