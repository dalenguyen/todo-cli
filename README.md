todocli
=======

Todo list command with [oclif](https://github.com/oclif/oclif) and TypeScript

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
This project has not been published to NPM package yet. If you want to use it, please replace __todocli__ with __./bin/run__.

For example, to show all tasks:

```sh
./bin/run show
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`todocli add`](#todocli-add)
* [`todocli help [COMMAND]`](#todocli-help-command)
* [`todocli remove`](#todocli-remove)
* [`todocli show`](#todocli-show)
* [`todocli update`](#todocli-update)

## `todocli add`

Adds a new todo

```
USAGE
  $ todocli add

OPTIONS
  -n, --task=task  task

DESCRIPTION
  ...
     Adds a new todo to the existing list
```

_See code: [src/commands/add.ts](https://github.com/dalenguyen/todocli/blob/v0.0.0/src/commands/add.ts)_

## `todocli help [COMMAND]`

display help for todocli

```
USAGE
  $ todocli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.6/src/commands/help.ts)_

## `todocli remove`

Removes a task by id

```
USAGE
  $ todocli remove

OPTIONS
  --id=id  (required) id of the task

DESCRIPTION
  ...
     Removes a task permanently from database by id
```

_See code: [src/commands/remove.ts](https://github.com/dalenguyen/todocli/blob/v0.0.0/src/commands/remove.ts)_

## `todocli show`

Shows existing tasks

```
USAGE
  $ todocli show

DESCRIPTION
  ...
     Shows all the tasks sorted by their ids
```

_See code: [src/commands/show.ts](https://github.com/dalenguyen/todocli/blob/v0.0.0/src/commands/show.ts)_

## `todocli update`

Marks a task as done

```
USAGE
  $ todocli update

OPTIONS
  --id=id  (required) id of the task

DESCRIPTION
  ...
     Marks a task as done
```

_See code: [src/commands/update.ts](https://github.com/dalenguyen/todocli/blob/v0.0.0/src/commands/update.ts)_
<!-- commandsstop -->

## Reference

[How to build a CLI tool in NodeJS](https://medium.freecodecamp.org/how-to-build-a-cli-tool-in-nodejs-bc4f67d898ec)