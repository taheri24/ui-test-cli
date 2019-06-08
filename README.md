ui-test-cli
===========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/ui-test-cli.svg)](https://npmjs.org/package/ui-test-cli)
[![Downloads/week](https://img.shields.io/npm/dw/ui-test-cli.svg)](https://npmjs.org/package/ui-test-cli)
[![License](https://img.shields.io/npm/l/ui-test-cli.svg)](https://github.com/taheri24/ui-test-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g ui-test-cli
$ ui-test-cli COMMAND
running command...
$ ui-test-cli (-v|--version|version)
ui-test-cli/0.0.0 win32-x64 node-v12.2.0
$ ui-test-cli --help [COMMAND]
USAGE
  $ ui-test-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ui-test-cli hello [FILE]`](#ui-test-cli-hello-file)
* [`ui-test-cli help [COMMAND]`](#ui-test-cli-help-command)

## `ui-test-cli hello [FILE]`

describe the command here

```
USAGE
  $ ui-test-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ui-test-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/taheri24/ui-test-cli/blob/v0.0.0/src\commands\hello.ts)_

## `ui-test-cli help [COMMAND]`

display help for ui-test-cli

```
USAGE
  $ ui-test-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.0/src\commands\help.ts)_
<!-- commandsstop -->
