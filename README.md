# pfileshot
Simple tool to get accessed files by a process and diff


## Requirements
Current requirements are `opensnoop` for Mac or `strace` for Linux and `shasum` commands.

Of course also Bash.


## Usage
With `pfileshot` you can get shots of files accessed by processes and compare different shots.

First take 2 shots by process name:
```
pfileshot shot process_name file_name
```

Then you can visualize an diff with less:
```
pfileshot diff file_name_a file_name_b
```


## License
This repository is under MIT license.
