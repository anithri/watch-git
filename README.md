# watch-git
A set of scripts and config to privde a git status summary in i3blocks or similar tool.

### watch-git
watch-git handles setting and viewing the currently watched git repo.

```shell
$ pwd
> /home/anithri/workspace/watch-git

$ watch-git help
> USAGE:
>    watch-git                    # => same as $cmd get all
>    watch-git get all
>    watch-git get name
>    watch-git get repo
>    watch-git set <path>         # => name defaults to basename <path>
>    watch-git set <name> <path>

$ watch-git set .
$ watch-git get all
watch-git
/home/anithri/workspace/watch-git

$ watch-git get name
watch-git

$ watch-git get repo
/home/anithri/workspace/watch-git

$ cd /
$ watch-git set playspace/another_project
$ watch-git get all
another_project
/home/anithri/playspace/watch-git

$ watch-git set favorite /home/anithri/batcave
$ watch-git get all
favorite
/home/anithri/batcave

