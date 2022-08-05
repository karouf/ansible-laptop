# ansible-laptop

I use this to set up a new laptop from scratch whenever I'd need to reinstall.

## One line installer

```bash
curl -sSL https://renaudmarti.net/new-machine | sh
```

## Detailed usage

Initial setup:
```bash
$ git clone https://github.com/karouf/ansible-laptop.git
$ ./bin/bootstrap
```

To run Ansible:
```bash
$ ./bin/converge
```

## Supported distributions

This has been tested on:
- Debian 11
- Ubuntu 22.04
