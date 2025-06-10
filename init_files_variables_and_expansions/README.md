# Linux Fundamentals Assignment

This project covers key Linux shell concepts such as shell variables, expansions, arithmetic operations, aliases, and initialization files. All scripts are written in Bash, are exactly two lines long, and are executable. The goal is to demonstrate the use of various Linux commands and shell features through short, functional scripts.

---

## Scripts and Descriptions

- `0-alias` — Creates an alias named `ls` with the value `rm *`.
- `1-hello_you` — Prints “hello” followed by the current user.
- `2-path` — Adds `/action` to the `PATH` environment variable.
- `3-paths` — Lists all directories in `PATH`, one per line.
- `4-global_variables` — Prints all global (environment) variables.
- `5-local_variables` — Prints local variables, environment variables, and shell functions.
- `6-create_local_variable` — Creates a local variable `BEST` with value `School`.
- `7-create_global_variable` — Creates a global variable `BEST` with value `School`.
- `8-true_knowledge` — Adds 128 to the value of `TRUEKNOWLEDGE` and prints the result.
- `9-divide_and_rule` — Divides `POWER` by `DIVIDE` and prints the result.
- `10-love_exponent_breath` — Raises `BREATH` to the power of `LOVE` and prints the result.
- `11-binary_to_decimal` — Converts the binary value of `BINARY` to a decimal number.
- `12-combinations` — Prints all combinations of two different letters.
- `13-print_float` — Prints the number stored in `NUM` with 2 decimal places.

---

## Requirements

- All scripts must begin with `#!/bin/bash`
- Each script must be exactly 2 lines long
- You must not use `&&`, `||`, or `;`
- You must not use `awk`, `sed`, or `bc`
- All scripts must be executable
- Scripts tested on Ubuntu 20.04 LTS
