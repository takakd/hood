<!--
<p align="center"><img src="docs/logo.svg" width="80"/></p>
-->

<h1 align="center">Hood</h1>

<p align="center">Shell utility which loads a temporary rc file</p>

<p align="center">
    <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/a568b3692dcc72af17d4abfed1b2c81d47f05dcaaefb021c9f9d3d6a856d3e6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d696e666f726d6174696f6e616c3f7374796c653d666c6174"><img src="https://camo.githubusercontent.com/a568b3692dcc72af17d4abfed1b2c81d47f05dcaaefb021c9f9d3d6a856d3e6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d696e666f726d6174696f6e616c3f7374796c653d666c6174" alt="License-MIT" data-canonical-src="https://img.shields.io/badge/License-MIT-informational?style=flat" style="max-width:100%;"></a>
</p>

<!--
<p align="center">
    <a href="https://retranslate-demo.herokuapp.com/"><strong>Demo</strong></a>
</p>
-->

<br>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Usage](#usage)
- [Development](#development)
  - [Tech stacks](#tech-stacks)
  - [Setup](#setup)
    - [Requirements](#requirements)
    - [Install](#install)
- [Get in touch](#get-in-touch)
- [Contributing](#contributing)
- [License](#license)

## Features

- Load run-command file in a current terminal

## Usage

1. Add run-command files for activating and deactivating.

Place activate rc file in `rc/[name]_activate`, deactivate one in `rc/[name]_deactivate`.

2. Load "rc/[name]_activate" run-command file.

```sh
$ hood [name]
```

3. After some working finished, Load "rc/[name]_deactivate" if it exists.

```sh
$ unhood
```

## Development

Hood is inspired by [`venv module`](https://docs.python.org/3/library/venv.html)

### Tech stacks

- Shell script

### Setup

#### Requirements

- zsh

Tested zsh 5.8 (x86_64-apple-darwin20.0) on macOS 11.2.3

#### Install

Add the path of Hood script to PATH environment variable.

e.g. 

```sh
echo "export PATH=<Hood root>/bin:$PATH" >> ~/.zshrc
```

## Get in touch

- [Dev.to](https://dev.to/takakd)
- [Twitter](https://twitter.com/takakdkd)

## Contributing

Issues and reviews are welcome. Don't hesitate to create issues and PR.

## License

&copy; 2021 takakd