# Linux

- search for a file

```
find /path/to/dir -name "file_nmae_to_be_searched.html"
```

- search for a text in a file

```
grep -r "string to be searched"  /path/to/dir
```


- Find all git hub directories 

```
find /home/ -name .git -type d -prune
```
(with `-prune` will not search `.git` directories themselves)
