# Gitignore Cheat Sheet

| Pattern | Explanation/Matches | Example |
| ------- | ----------- | ------- |
| `filename` | Ignore a specific file | `log.txt` |
| `dirname/` | Ignore a specific directory | `build/` |
| `*.extension` | Ignore files with a specific extension | `*.log` |
| `!filename` | Include a previously ignored file | `!config.ini` |
| `/path/to/file` | Ignore a file with a specific path | `/src/config.ini` |
| `#` | Comments in the .gitignore file | `# This is a comment` |
| `*` | Ignore any character | `temp*` |
| `?` | Ignore a single character | `temp?.txt` |
| `[abc]` | Ignore characters in brackets | `[abc]file.txt` |
| `![abc]` | Include files with characters in brackets | `![abc]file.txt` |
| `**/` | Ignore any subdirectory | `logs/**/` |
