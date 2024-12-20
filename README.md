## Description

### pre-commit

Calls `laravel/pint` before doing commit.

### prepare-commit-msg

Hook automatically puts a task number recognized from branch name to the commit message as "Refs: #{ticket-number}". Written in PHP.

## Usage

Copy the script file into `.git/hooks` in your project's folder.
