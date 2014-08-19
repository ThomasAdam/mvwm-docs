```
## Formatting

Please keep file format as follows:
   -- Lines should be no longer than 75 characters
   -- All nested structures should be commented at their beginning and end
   -- All codeblocks should be commented at their beginning and end
   -- If the file contains a lot of formatting, keep paragraphs or other 
      logical parts separated by a commented out line and/or comment their
      beginnings and ends
 
For vim users:

au BufNewFile,BufRead *.mdoc set filetype=groff
au BufNewFile,BufRead *.mdoc match ErrorMsg '\%>75v.\+'

dictionary:
section:
  - header - .Sh
  - link   - .Sx
```
