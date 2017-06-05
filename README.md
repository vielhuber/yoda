# 🥝 kiwi 🥝

**kiwi provides a git-like experience for relational databases.**

* no sql triggers
* no binary / ddl logs
* works with any shared hosting provider
* data and schema changes, at the same time
* blazingly fast
* command line tool usage
* requires only ssh access to remote repository
* open source and free
* support for both mysql and postgresql
* search/replace layer for environment specific values (serialize safe!)
* test suite available

## Disclaimer

This does not prevent you from taking backups. Use this script at your own risk.

## Installation

Install globally:
```
composer global require vielhuber/kiwi
```
Add to PATH:
```
~/.composer/vendor/kiwi/src (unix)
%APPDATA%\Composer\vendor\vielhuber\kiwi\src (windows)
```

## Usage

first setup kiwi on client:

`kiwi init`

get current status:

`kiwi status`

push changes to remote repo:

`kiwi push`

pull state of remote repo:

`kiwi pull`
