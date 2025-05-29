# NvChad

The mapping configuration uses the nvim name shortcuts as:
```
  <C>      ->  Ctrl 
  <leader> ->  Space
  <A>      ->  alt
  <S>      ->  shift
```

The default mappings are defined [here](https://github.com/NvChad/NvChad/blob/v2.5/lua/nvchad/mappings.lua).

## Operating on the Visual area

### How to Enter Vim Visual Mode
There are three different visual modes in Vim.

| Shortcut | Description |
| --- | --- |
| v | Character-wise visual mode |
| V | Line-wise visual mode |
| Ctrl + v | Block-wise visual mode |

### Character-wise visual mode cheatsheet

| Shortcut | Description |
| --- | --- |
| v + 0 | Start of line |
| v + $ | End of line |
| v + b | Prev word |
| v + B | Prev WORD |
| v + w | Next word |
| v + W | Next WORD |
| v + e | Next end of word |
| v + E | Next end of WORD |
| v + f | Extension window |
| v + F | Extension window |
| v + c | Extension window |
| v + d | Extension window |
| v + G | Extension window |

### How to Exit Vim Visual Mode
There are three ways to exit visual mode:
- Esc
- Ctrl + c
- Same key as your current visual mode

