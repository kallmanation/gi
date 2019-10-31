# gi
## The Git Interpolator

Simple shell configuration to help with simple typos while typing the `git` command.

## Features

Two aliases `it` and `gti` both mapped to `git`.

The interpolator `gi` which removes a leading `t` from its params before passing them all to `git`.

## Examples

```sh
$ it status
# Becomes: git status
...
$ gti pull
# Becomes: git pull
...
$ gi tdiff
# Becomes: git diff
...
$ gi push
# Becomes: git push
```

## Installation

### By clone and source

First, clone this repository somewhere on your machine:
```sh
$ git clone git@github.com:kallmanation/gi.git
```

Then add the following line to your `~/.bashrc` or `~/.zshrc` or similar:
```sh
source path/to/gi/girc
```

### By copy and paste

Open the contents of [`girc`](https://raw.githubusercontent.com/kallmanation/gi/master/girc) and copy them into your `~/.bashrc` or `~/.zshrc` or similar.
