# multitran_cli
Command-line interface for multitran.ru

# installation

## with zplug

```sh
zplug "nogizhopaboroda/multitran_cli", as:command, use:translate
```

## manual

```sh
curl https://github.com/nogizhopaboroda/multitran_cli/blob/master/translate -o /usr/local/bin/translate && chmod +x /usr/local/bin/translate
```


## can be used directly from github

```sh
python <(curl -fsSL https://raw.githubusercontent.com/nogizhopaboroda/multitran_cli/master/translate) [arguments]
```

# arguments

```sh
$ translate

usage: translate [-h] [-R] [-S] [-L [LANG]] [--lang-list] [word]

positional arguments:
  word                  word to translate

optional arguments:
  -h, --help                show this help message and exit
  -R, --reverse             Reverse data (last block to first block)
  -S, --short               Print short output (only first block)
  -L [LANG], --lang [LANG]  Language
  --lang-list               Print languages list and exit

```
