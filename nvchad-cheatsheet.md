# NvChad

The mapping configuration uses the nvim name shortcuts as:
```
  <C>      ->  Ctrl 
  <leader> ->  Space
  <A>      ->  alt
  <S>      ->  shift
```

The default mappings are defined [here](https://github.com/NvChad/NvChad/blob/v2.5/lua/nvchad/mappings.lua).

## NvChad Cheet Sheet
| Shortcut | Description |
| --- | --- |
| \<leader\> + ch | NvChad Cheat Sheet |

## WhichKey
| Shortcut | Description |
| --- | --- |
| \<leader\> + wk | Query lookup |
| \<leader\> + wK | All keymaps |

## General

| Shortcut | Description |
| --- | --- |
| Esc | Clear highlights |
| u | Undo |
| \<leader\> + fm | Format file |
| \<leader\> + / | Comment |
| gcc | Comment line |
| \<C\> - c | Copy whole file |
| \<C\> - s | Save file |

## Terminal

| Shortcut | Description |
| --- | --- |
| \<leader\> + v | Start of line |
| \<leader\> + h | End of line |
| \<A\> - i | Toggle floating terminal |
| \<A\> - h | Toggleable horizontal terminal |
| \<A\> - v | Toggleable vertical terminal |

## Switch

| Shortcut | Description |
| --- | --- |
| \<C\> - h | Window left |
| \<C\> - j | Window down |
| \<C\> - k | Windows up |
| \<C\> - l | Window right |

## Buffer
| Shortcut | Description |
| --- | --- |
| TAB | Window left |
| \<leader\> + x | Window down |
| <S> - TAB | Windows up |

## Add
| Shortcut | Description |
| --- | --- |
| [ + \<leader\> | Empty line above cursor |
| ] + \<leader\> | Empty line below cursor |

## CMD

| Shortcut | Description |
| --- | --- |
| ; | Enter command mode |

## Nvimtree
| Shortcut | Description |
| --- | --- |
| \<leader\> + e | Focus window |
| \<C\> - n | Toggle window |

## Telescope
| Shortcut | Description |
| --- | --- |
| \<leader\> + fa | Find all file |
| \<leader\> + ff | Find file |
| \<leader\> + th | NvChad themes |
| \<leader\> + pt | Pick hidden terminal |
| \<leader\> + gt | Git status |
| \<leader\> + cm | Git commit |
| \<leader\> + fz | Find in current buffer |
| \<leader\> + fo | Find oldfiles |
| \<leader\> + ma | Find marks |
| \<leader\> + fh | Help page |
| \<leader\> + fb | Find buffers |
| \<leader\> + fw | Live grep |


## Operating on the Visual area

### How to Enter Vim Visual Mode
There are three different visual modes in Vim.

| Shortcut | Description |
| --- | --- |
| v | Character-wise visual mode |
| V | Line-wise visual mode |
| Ctrl - v | Block-wise visual mode |

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





