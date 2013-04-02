# catacomb

## Installation

Using [fresh], run the following:

```
fresh twe4ked/catacomb bin/catacomb --bin
```

Manually:

```
mkdir ~/bin/
wget https://raw.github.com/twe4ked/catacomb/master/bin/catacomb ~/bin/catacomb
export PATH="$PATH:~/bin/"
# the PATH will need to be set in your shell config
```

## Notes

* Encrypts using the first key retrieved from GitHub
* Decrypts using `~/.ssh/id_rsa`

## Licence

MIT.

[fresh]: https://github.com/freshshell/fresh
