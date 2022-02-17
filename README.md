# shell-magics
Some shell magics you need in daily life 


### Copy or move all files in a directory regardles of folder depth or number
```shell
  find ./pictures -name '*.*' | xargs -I files mv files ./results
```
