# watch-git
A set of scripts and config to privde a git status summary in i3blocks or similar tool.

# watch-git
watch-git handles setting and viewing the currently watched git repo.

```shell
$ watch-git set . # > sets pwd as the weatched repo
$ watch-git get all
> USAGE:
>    watch-git                    # => same as $cmd get all
>    watch-git get all
>    watch-git get name
>    watch-git get repo
>    watch-git set <path>         # => name defaults to basename <path>
>    watch-git set <name> <path>
