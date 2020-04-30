# Linux

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

# Github

- `.git' is the folder containing information about the repository, check for example `config` file in this folder to see the origin of the repository. 

- Update local copy 

```
git pull origin master
```

# Vim 

-  To quit type `:q`


1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
