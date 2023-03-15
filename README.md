# lldb-tips


### Connect to a remote session

Phone:
```
# ./lldb-server platform --listen "*:31337" --server
```

Laptop
```
$ lldb
(lldb)

```

### Get shared object information (e.g. ASLR base address)
```
(lldb) image dump sections libdiaul.so 
```

### Setting breakpoints

Breakpoint on function name
```
(lldb) breakpoint set --name Diaul_func
```
