# Playbook-template

- env.yml
    - **role-helloworld** : Echo single phrase

## Init project

From 0 :
`rm -f .manala.yaml && manala init --repository=https://github.com/loic-roux-404/manala-recipes`

From skelet : `manala up`

## Documentation

[Check recipes README](https://github.com/loic-roux-404/manala-recipes/blob/master/README.md)

## Requirements

[Recommanded] a python virtual env :
- `conda create --name=(basename "$PWD") python=3.8`
- `conda activate (basename "$PWD")`

- then : `make install`

See [Makefile](Makefile) for debugging and full deploy on a server

## License

BSD

## Author Information

[Loic Roux](https://github.com/loic-roux-404)
