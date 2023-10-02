```
Generate automatic command index from a program.

Usage:
    make-readme [options] COMMAND

It outputs a Markdown section with program name, 
help and version information.

Works for any installed program that has --help
and --version options. Especially useful for Docopt.
It can be used with the following command to generate readme files:
    pip install -e .

Options:
    -h LEVEL, --heading LEVEL  Start from hLEVEL heading [default: 2].
    --help     Display this message.
    --version  Display version information.
```