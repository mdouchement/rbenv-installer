# rbenv installer

This tool is used to install `rbenv` and some plugins.

Ths repository is based on **fesplugas** `rbenv-installer` repository.


## Requirements

- Git
- Curl


## Install

Install [rbenv] and friends by running:

```sh
curl https://raw.githubusercontent.com/mdouchement/rbenv-installer/master/bin/rbenv-installer | bash
```


## Installing a Ruby

Install latest stable Ruby and make it global:

```sh
rbenv install 2.5.0
rbenv global 2.5.0
```


## Updating

Update `rbenv` and plugins provided by the installer running:

```sh
rbenv update
```


## Bootstrap

<details>
<summary>Not ported</summary>

If you are installing `rbenv` in Ubuntu you'll probably need to install
some required packages. You can use the provided `bootstrap` scripts.

```sh
rbenv bootstrap-ubuntu-12-04
```

</details>

## License

**MIT**

## About rbenv

**rbenv** source code is available at <https://github.com/rbenv/rbenv>

[rbenv]: https://github.com/rbenv/rbenv
