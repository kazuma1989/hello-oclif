hello-oclif
===========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/hello-oclif.svg)](https://npmjs.org/package/hello-oclif)
[![CircleCI](https://circleci.com/gh/kazuma1989/hello-oclif/tree/master.svg?style=shield)](https://circleci.com/gh/kazuma1989/hello-oclif/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/hello-oclif.svg)](https://npmjs.org/package/hello-oclif)
[![License](https://img.shields.io/npm/l/hello-oclif.svg)](https://github.com/kazuma1989/hello-oclif/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g hello-oclif
$ hello-oclif COMMAND
running command...
$ hello-oclif (-v|--version|version)
hello-oclif/0.0.0 darwin-x64 node-v13.8.0
$ hello-oclif --help [COMMAND]
USAGE
  $ hello-oclif COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`hello-oclif hello [FILE]`](#hello-oclif-hello-file)
* [`hello-oclif help [COMMAND]`](#hello-oclif-help-command)

## `hello-oclif hello [FILE]`

describe the command here

```
USAGE
  $ hello-oclif hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ hello-oclif hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/kazuma1989/hello-oclif/blob/v0.0.0/src/commands/hello.ts)_

## `hello-oclif help [COMMAND]`

display help for hello-oclif

```
USAGE
  $ hello-oclif help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
