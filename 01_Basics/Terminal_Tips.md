# Terminal Tips

## Command History

Show command history:

```bash
history
```

Search history:

```bash
history | grep cp
```

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `↑ / ↓` | Previous / next command |
| `Tab` | Autocomplete commands and paths |
| `Ctrl + L` | Clear the terminal screen |
| `Ctrl + R` | Search command history |

## Help

Quick help:

```bash
ls --help
```

Manual page:

```bash
man ls
```

Inside `man`:

- `↑ / ↓` — scroll
- `Space` — next page
- `q` — quit

## Pipe

```bash
history | grep backup
```

`|` sends the output of the first command to the next command.
