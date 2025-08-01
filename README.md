# 0x03. Shell, init files, variables and expansions

## 📚 Description

This project focuses on understanding the shell environment, initialization files, shell variables (local and global), shell arithmetic, expansions, aliases, and executing scripts in the current shell context. It is a fundamental part of learning how Bash works under the hood.

## 🗂️ Project Structure

| Filename | Description |
|----------|-------------|
| `0-alias` | Creates an alias named `ls` with value `rm *` |
| `1-hello_you` | Prints "hello `<user>`", where `<user>` is the current Linux username |
| `2-path` | Adds `/action` to the end of the `PATH` environment variable |
| `3-paths` | Counts the number of directories in the current `$PATH` |
| `4-global_variables` | Lists all global (environment) variables |
| `5-local_variables` | Lists all local variables, environment variables, and shell functions |
| `6-create_local_variable` | Creates a local variable named `BEST` with the value `School` |
| `7-create_global_variable` | Creates a global variable named `BEST` with the value `School` |
| `8-true_knowledge` | Adds `128` to the value stored in `$TRUEKNOWLEDGE` and prints the result |
| `9-divide_and_rule` | Divides the value of `$POWER` by `$DIVIDE` and prints the result |
| `10-love_exponent_breath` | Raises the value of `$BREATH` to the power of `$LOVE` |
| `11-binary_to_decimal` | Converts the binary number stored in `$BINARY` to decimal |
| `12-combinations` | Prints all 2-letter combinations of lowercase letters (except `oo`) |
| `13-print_float` | Prints the value of `$NUM` rounded to two decimal places |

---

## 🧪 Requirements

- All scripts are written in **Bash**
- Must be exactly **2 lines** long (`wc -l file` returns `2`)
- Must begin with the shebang: `#!/bin/bash`
- Must be executable: `chmod +x filename`
- Should not use: `&&`, `||`, `;`, `bc`, `sed`, or `awk`
- Files must end with a **newline**
- Tested on **Ubuntu 20.04 LTS*
