![Banner](https://user-images.githubusercontent.com/63385587/135638876-40268882-77ac-42a0-ace5-74ff1b5ae2e6.png)

<div align="center">
<a href="https://oclif.io" target="_blank"><img src="https://img.shields.io/badge/cli-oclif-brightgreen.svg" alt="oclif" /></a>
<a href="https://npmjs.org/package/noteli" target="_blank"><img src="https://img.shields.io/npm/v/noteli.svg" alt="Version" /></a>
<a href="https://npmjs.org/package/noteli" target="_blank"><img src="https://img.shields.io/npm/dw/noteli.svg" alt="Downloads/Week" /></a>
<a href="https://github.com/sahilpabale/noteli/blob/master/package.json" target="_blank"><img src="https://img.shields.io/npm/l/noteli.svg" alt="License" /></a>

</div>

# Contents
<!-- toc -->
* [noteli](#noteli)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->
```sh-session
$ npm install -g noteli
$ noteli COMMAND
running command...
$ noteli (-v|--version|version)
noteli/1.5.4 win32-x64 node-v14.16.1
$ noteli --help [COMMAND]
USAGE
  $ noteli COMMAND
...
```
<!-- usagestop -->

# Commands

<!-- commands -->
* [`noteli create`](#noteli-create)
* [`noteli delete <ID>`](#noteli-delete-id)
* [`noteli help [COMMAND]`](#noteli-help-command)
* [`noteli login`](#noteli-login)
* [`noteli logout`](#noteli-logout)
* [`noteli read`](#noteli-read)
* [`noteli update <ID>`](#noteli-update-id)
* [`noteli whoami`](#noteli-whoami)

## `noteli create`

create a new note

```
USAGE
  $ noteli create

DESCRIPTION
  Helps you create a fresh new Note :)
```

_See code: [src/commands/create.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/create.ts)_

## `noteli delete <ID>`

delete your note(s)

```
USAGE
  $ noteli delete <ID>

DESCRIPTION
  You can delete some specific notes if you think they are not worthy.

EXAMPLE
  $ noteli delete 2
```

_See code: [src/commands/delete.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/delete.ts)_

## `noteli help [COMMAND]`

display help for noteli

```
USAGE
  $ noteli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

## `noteli login`

login the user for noteli

```
USAGE
  $ noteli login

DESCRIPTION
  Uses Auth0 Social Login to authorize user using browser.
```

_See code: [src/commands/login.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/login.ts)_

## `noteli logout`

logout the user from noteli

```
USAGE
  $ noteli logout

DESCRIPTION
  Revokes the token and logs out user from system.
```

_See code: [src/commands/logout.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/logout.ts)_

## `noteli read`

read all your notes

```
USAGE
  $ noteli read
  $ noteli read <ID>

DESCRIPTION
  You can read all your notes or some specific note too.

EXAMPLES
  $ noteli read
  $ noteli read 2
```

_See code: [src/commands/read.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/read.ts)_

## `noteli update <ID>`

update your note(s)

```
USAGE
  $ noteli update <ID>

DESCRIPTION
  You can update some specific notes if you think they need some change.

EXAMPLE
  $ noteli update 2
```

_See code: [src/commands/update.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/update.ts)_

## `noteli whoami`

shows the current logged-in user

```
USAGE
  $ noteli whoami

DESCRIPTION
  Checks for the token and verifies with Auth0 for authencticity.
```

_See code: [src/commands/whoami.ts](https://github.com/sahilpabale/noteli/blob/v1.5.4/src/commands/whoami.ts)_
<!-- commandsstop -->

### Thats It, Enjoy `noteli`
