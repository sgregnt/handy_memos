# Linux and Shell

- Search for a file
```
find /path/to/dir -name "file_nmae_to_be_searched.html"
```

- Search for a text in a file
```
grep -r "string to be searched"  /path/to/dir
```


- Find all git hub directories 
```
find /home/ -name .git -type d -prune
```
(with `-prune` will not search `.git` directories themselves)


- Show all hidden files (such as files starting with `.`)

```
ls -a
```

- Remove directory 
```
rm -r /path/to/dir
```

or 

```
rm -rf /path/to/dir
```
...to avoid interactive mode. 

- Create file 

```
touch file_to_be_created.txt
```

- Open new terminal `CTRL + SHIFT + T`

- To view shell hostory type `history`

- Show hidden files in explorer (Ubunto) toggle `CTRL + H`

# Github

- `.git' is the folder containing information about the repository, check for example `config` file in this folder to see the origin of the repository. 

- Fix pdf corruption with end line changes from CRLF to LF, by placing `.gitattributes` in `.git\info\` the contents should be
```
*.exe binary 
*.pdf binary
```
(`#` comments things out)

- Update local copy 

```
git pull origin master
```

- Undo `git add`



# Vim 

-  To quit type `:q`
