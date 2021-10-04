# git

> Distributed version control system.
> Some subcommands such as `commit`, 'checkout', etc. have their own usage documentation. To see them use `tldr git {{subcommand}}`.
> More information: <https://git-scm.com/>.

- Check the Git version:

`git --version`

- Show general help:

`git --help`

- Show help on a Git subcommand (like 'clone', 'branch', 'checkout', 'push', `log`, etc.):

`git help {{subcommand}}`

- Execute a Git subcommand:

`git {{subcommand}}`

- Execute a Git subcommand on a custom repository root path:

`git -C {{path/to/repo}} {{subcommand}}`

- Execute a Git subcommand with a given configuration set:

`git -c '{{config.key}}={{value}}' {{subcommand}}`
