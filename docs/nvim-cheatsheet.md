# Neovim cheatsheet

Only the keys defined in `nvim/dotfiles.lua`. Vim built-ins, kickstart.nvim keys
and plugin defaults are left out. `<Space>` is the leader key.

## Navigation and search

| Key | Mode | Action |
| --- | --- | --- |
| `/` | normal | Search in the file, pre-filled with the word under the cursor |
| `gh` | normal | Find files (Telescope) |
| `g/` | normal | Live grep the project (Telescope) |
| `g/` | visual | Grep the project for the selection (Telescope) |
| `Ctrl-o` | normal | Back to the previous file in the jump list, skipping jumps inside the same file |
| `Ctrl-p` | normal | Forward to the next file in the jump list |

## Buffers

| Key | Action |
| --- | --- |
| `gn` | Next buffer |
| `gp` | Previous buffer |
| `<Space>bd` | Delete the buffer; closes the tab when it is the tab's only editor window |
| `<Space>yr` | Copy the file's path, relative to the project root |
| `<Space>ya` | Copy the file's absolute path |

## Tabs

| Key | Action |
| --- | --- |
| `<Space>tn` | New tab |
| `<Space>tw` | Save every modified file shown in this tab |
| `<Space>tq` | Close this tab and discard its changes; on the last tab, quits nvim |

## LSP (buffers with a language server)

| Key | Action |
| --- | --- |
| `gd` | Go to definition |
| `gD` | Go to declaration |
| `gy` | Go to type definition |
| `gI` | Go to implementation |
| `gA` | Find all references |
| `gs` | Symbols in the file |
| `gS` | Symbols in the project |
| `g.` | Code actions |
| `cd` | Rename the symbol |
| `g]` | Next diagnostic, with a float |
| `g[` | Previous diagnostic, with a float |

## Git

| Key | Action |
| --- | --- |
| `<Space>gb` | Blame the whole file (gitsigns) |

## File tree (neo-tree)

| Key | Where | Action |
| --- | --- | --- |
| `Tab` | editor | Reveal the current file in the tree |
| `Tab` | tree | Back to the previous window |
| `l`, `o`, `zo` | tree | Open the file or expand the folder |
| `h`, `zc` | tree | Collapse the folder |
| `Shift-Enter` | tree | Open in a new tab |
| `c` | tree | Copy the node, to paste elsewhere in the tree |
| `Y` | tree | Copy the node's path, relative to the working directory |
| `gy` | tree | Copy the node's absolute path |

## netrw (`:Ex`)

| Key | Action |
| --- | --- |
| `gh` | Find files in the folder being browsed (Telescope) |
| `g.` | Show or hide dot-files |
