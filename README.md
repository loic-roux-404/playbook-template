# Playbook-template
> Branch differ from master by the use of single inventory and group_vars

Env Playbook: 

**role-basics** &rarr; Simple role to create shell / users / ssh keys from github

## Init project

From 0 : 
`rm -f .manala.yaml && manala init --repository=https://github.com/loic-roux-404/manala-recipes`

From skelet : `manala up`

## Documentation

[Check recipes README](https://github.com/loic-roux-404/manala-recipes/blob/master/README.md)

## Requirements

`make install` 

See [Makefile](Makefile) for debugging and full deploy on a server

## TO DO

- [ ] molecule test

## License

BSD

## Author Information

[Loic Roux](https://github.com/loic-roux-404)
