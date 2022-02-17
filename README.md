# Shell-magics
Some shell magics you need in daily life
Note: for windows you can use `Git Bash`


#### Move all files (with wildcard) in a directory (recursively) regardles of folder depth or number , use `cp` for copying

```shell
  find ./input -name '*.*' | xargs -I files mv files ./output
```
