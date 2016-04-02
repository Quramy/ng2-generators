# ng2gen
is a shell-based project generator for Angular2.

This generates the following project templates:

* Simple project with browserify build
* Simple project with webpack build
* Simple project with Sass


## Install

Copy the following and paste in your terminal:

### zsh

```sh
git clone https://github.com/Quramy/ng2-generators ${HOME}/.ng2gen && echo "alias ng2gen='/bin/sh ${HOME}/.ng2gen/ng2gen'" >> ${HOME}/.zshrc && source ${HOME}/.zshrc
```

### bash

```sh
git clone https://github.com/Quramy/ng2-generators ${HOME}/.ng2gen && echo "alias ng2gen='/bin/sh ${HOME}/.ng2gen/ng2gen'" >> ${HOME}/.bachrc && source ${HOME}/.bashrc
```

Or clone this repository and add the directory to the `$PATH` var.

## Usage

```text
Usage: ng2gen [OPTIONS] [APP_NAME]
  Project generator for Angualr2.

Options:
  -h, --help
      --version
  -g, --generator [GENERATOR_NAME]
```

