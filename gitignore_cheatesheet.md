# Gitignore Cheat Sheet
## Pattern Examples

- `*.txt` - Ignore all files with the `.txt` extension.
- `/dir` - Ignore the directory `dir` in the root directory.
- `dir/` - Ignore all files and subdirectories in the directory `dir`.
- `!important.txt` - Include the file `important.txt`, even if it matches a previous pattern.
- `/build/` - Ignore the `build` directory.
- `/node_modules/` - Ignore the `node_modules` directory.
- `*.log` - Ignore all log files.
- `*.zip` - Ignore all zip files.
- `*.exe` - Ignore all executable files.
- `*.o` - Ignore all object files.

## Globbing

Gitignore files use glob patterns to match files and directories. Here are some common glob patterns:

- `*` - Matches any number of characters, except `/`.
- `?` - Matches any single character, except `/`.
- `**` - Matches any number of characters, including `/`.
- `[abc]` - Matches any character in the set `a`, `b`, or `c`.
- `[a-z]` - Matches any character in the range `a` to `z`.
- `[!abc]` - Matches any character not in the set `a`, `b`, or `c`.
- `[!a-z]` - Matches any character not in the range `a` to `z`.
