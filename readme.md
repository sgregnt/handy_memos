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

- `.git` is the folder containing information about the repository, check for example `config` file in this folder to see the origin of the repository. 

- (Didn't work) Fix pdf corruption with end line changes from CRLF to LF, by placing `.gitattributes` in `.git\info\` the contents should be
```
*.exe binary 
*.pdf binary
```
(`#` comments things out)

- Update local copy 

```
git pull origin master
```

- To undo `git add` do `git reset`

# Python 

-  [Complexity of python operations](https://www.ics.uci.edu/~pattis/ICS-33/lectures/complexitypython.txt) 

# Vim 

-  To quit type `:q`


# Matplotlib

- To change backend has to add things of the form: `import matplotlib` and `matplotlib.use('TkAgg')` 


# Markdown 

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- Resize images 

```
<img src="https://github.com/sgregnt/geometric_processing_net/blob/master/pics/mesh_with_displacments.png" width="40%">

```
- Multiple images in the same line

```
<p float="left">
<img src="https://github.com/sgregnt/geometric_processing_net/blob/master/pics/compare_1.png" width="35%">
<img src="https://github.com/sgregnt/geometric_processing_net/blob/master/pics/compare_2.png" width="35%">
<img src="https://github.com/sgregnt/geometric_processing_net/blob/master/pics/compare_3.png" width="35%">
<img src="https://github.com/sgregnt/geometric_processing_net/blob/master/pics/compare_4.png" width="35%">
</p>
```
