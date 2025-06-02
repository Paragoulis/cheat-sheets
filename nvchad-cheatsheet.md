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
| h | Left |
| j | Down |
| k | Up |
| l | Right |
| / | Search forward |
| ? | Search backward |
| y | Yank |
| ! | Run program |
| 0 | Start of line |
| $ | End of line |
| b | Prev word |
| B | Prev WORD |
| w | Next word |
| W | Next WORD |
| e | Next end of word |
| E | Next end of WORD |
| f | Move to next char |
| F | Move to prev char |
| t | Move before next char |
| T | Move before prev char |
| c | Change |
| d | Delete |
| r | Replace |
| G | Last line |
| < | Indent left |
| > | Indent right |
| ^ | Start of line (non ws) |
| { | Prev empty line |
| } | Next empty line |

#### around ( v + a )
| Shortcut | Description |
| --- | --- |
| b | () block |
| B | {} block |
| ( | () block |
| ) | () block |
| [ | [] block |
| ] | [] block |
| { | {} block |
| } | {} block |
| < | <> block |
| > | <> block |
| p | Paragraph |
| s | Sentence |
| t | Tag block |
| w | Word with ws |
| W | WORD with ws |
| ' | ' string |
| " | " string |
| ` | ` string |

#### inside ( v + i )
| Shortcut | Description |
| --- | --- |
| b | Inner () |
| B | Inner {} |
| ( | Inner () |
| ) | Inner () |
| [ | Inner [] |
| ] | Inner [] |
| { | Inner {} |
| } | Inner {} |
| < | Inner <> |
| > | Inner <> |
| p | Inner paragraph |
| s | Inner sentence |
| t | Inner tag block |
| w | Inner word |
| W | Inner WORD |
| ' | Inner ' string |
| " | Inner " string |
| ` | Inner ` string |

### How to Exit Vim Visual Mode
There are three ways to exit visual mode:
- Esc
- Ctrl + c
- Same key as your current visual mode

## Terminal

| Shortcut | Description |
| --- | --- |
| <leader> + v | Start of line |
| <leader> + h | End of line |
| b | Prev word |
| B | Prev WORD |
| w | Next word |

