# ppc

(P)rint (P)assword (C)haracters. This very small bash script prints the specified
characters from a password you enter. Useful for websites and password forms
that ask for the Nth character and your password manager does not support
that.

```bash
Usage: ppc [N]...
Print Nth character(s) from a password
```

Example:

```bash
> ppc 1 3 5
Password: hello
h l o
>
```

Note the password is hidden when entered, it's shown above just for illustration
purposes.

## Installation

Clone the repo then in that same dir use the ninja build tool to install:

```bash
ninja
```

Or if you don't have ninja:

```bash
sudo cp ppc /usr/local/bin/
```

## License

GPL v3.0.
