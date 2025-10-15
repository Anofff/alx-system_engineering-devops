# 0x03 - Shell, init files, variables and expansions

This directory contains 2-line bash scripts for the ALX tasks.

## Files

- `0-alias`: alias `ls` to `rm *`. Test: `source ./0-alias` then `alias ls`.
- `1-hello_you`: prints `hello $USER`. Run: `./1-hello_you`.
- `2-path`: appends `/action` to `$PATH`. Test: `source ./2-path` and `echo $PATH`.
- `3-paths`: prints the number of directories in `$PATH`.
- `4-global_variables`: lists environment variables using `printenv`.
- `5-local_variables`: lists local vars, env vars, and functions via `set`.
- `6-create_local_variable`: sets local `BEST=\"School\"` (source to persist in shell).
- `7-create_global_variable`: exports `BEST=\"School\"`.
- `8-true_knowledge`: prints `128 + $TRUEKNOWLEDGE`.
- `9-divide_and_rule`: prints `$POWER / $DIVIDE`.
- `10-love_exponent_breath`: prints `$BREATH ** $LOVE`.
- `11-binary_to_decimal`: converts binary `$BINARY` to decimal.
- `12-combinations`: prints aa..zz excluding `oo`, one per line.
- `13-print_float`: prints `$NUM` with 2 decimal places.

## Notes

- All files are exactly 2 lines and executable.
- Avoid `&&`, `||`, `;`, `bc`, `sed`, `awk`.

