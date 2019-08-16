ppanther
========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/ppanther.svg)](https://npmjs.org/package/ppanther)
[![Downloads/week](https://img.shields.io/npm/dw/ppanther.svg)](https://npmjs.org/package/ppanther)
[![License](https://img.shields.io/npm/l/ppanther.svg)](https://github.com/takuma-watanabe/ppanther/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g ppanther
$ ppanther COMMAND
running command...
$ ppanther (-v|--version|version)
ppanther/0.0.0 darwin-x64 node-v12.8.0
$ ppanther --help [COMMAND]
USAGE
  $ ppanther COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ppanther hello [FILE]`](#ppanther-hello-file)
* [`ppanther help [COMMAND]`](#ppanther-help-command)

## `ppanther hello [FILE]`

describe the command here

```
USAGE
  $ ppanther hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ppanther hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/takuma-watanabe/ppanther/blob/v0.0.0/src/commands/hello.ts)_

## `ppanther help [COMMAND]`

display help for ppanther

```
USAGE
  $ ppanther help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_
<!-- commandsstop -->
