# ClassifiedFoldersPlugin

## Sample

### Folder Settings

```
recipe
  western
    fish
    meat
  japanese
    fish
    meat
```

### MTML

```
<mt:Pages id="94">
<mt:ClassifiedFolders><$mt:FolderLabel$><mt:Unless name="__last__"> > </mt:Unless></mt:ClassifiedFolders>
</mt:Pages>
```

### Output

```
recipe > western > fish 
```