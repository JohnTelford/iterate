June 03, 2024 - v0.1

# Building and Using — iteration reference


## Building

### Create GitHub Repo

Login to [github](https://github.com)

Create a GitHub Repository

### Path

Ensure $PATH includes path to Python 

- ```export PATH=“.:${PATH}:/usr/local/bin:”```

### Create Python venv

Create Python virtual environment

- [venv -- Creation of virtual environments](https://docs.python.org/3/library/venv.html)

Create Development Environment

- ```cd Documents```

Create Dev folder

- ```cd Documents/Dev/venv```

#### Create venv

- ``git clone https://github.com/JohnTelford/iteration_reference.git``

- ```python3.12 -m venv iteration_reference```

## Install Third Party Plugins

 ```cd iteration_reference```

`mdBook` can be extended with external commands

- [Third Party Plugins](https://github.com/rust-lang/mdBook/wiki/Third-party-plugins)

### Install mdbook

- [mdBook Docs](https://rust-lang.github.io/mdBook/)

Install `mdbook`

- ```cargo install mdbook```

Create a `mdbook`

- ```mdbook init```

### mdbook_admonish

- [mdbook-admonish](https://github.com/tommilligan/mdbook-admonish )

Install `mdbook-admonish` app

- ```cargo install mdbook-admonish```

Install mdbook-admonish in mdbook

- ```mdbook-admonish install```

<hr>

# References web Pages

June 04, 2024 v0.1

# Chapter 1

```admonish info
INFO
and then some
```

# Summary

- [Chapter 1](chapter_1.md)

# Book Toml

authors = ["JohnTelford"]
language = "en"
multilingual = false
src = "src"
title = "Iteration Website Development Reference v0.0.1"
