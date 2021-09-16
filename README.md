# one-liners


## Docker
### Remove all exited Docker containers:

```
alias docker_rm_exit="docker ps -a | grep Exit | cut -d ' ' -f 1 | xargs docker rm"
```
