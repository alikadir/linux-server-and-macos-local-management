[<< Back](README.md)

# File and Directory Management


### Rename file - directory
use mv command for rename
```bash
$ mv .old-file .new-file   
```

### Remove file - directory (recursivly)
-r = recursivly

-f = force
```bash
$ rm -r .node_modules  
```

### Tree view :)
-s = folder and file size (MB - KB)

-h = size mode humanfriendly

-L 2 = deep limit 

-C = colored

```bash
$ tree -s -h 
```

### Link (shortcut in windows)

-s = symbolic or soft link [for more info](https://linuxize.com/post/how-to-create-symbolic-links-in-linux-using-the-ln-command/)

```bash
$ sudo ln -s /opt/homebrew/bin/idb /usr/local/bin/idb
```

### Track changes on a file
-f = follow
```bash
$ tail -f ~/mylog.txt
```