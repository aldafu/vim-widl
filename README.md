# widl.vim Web IDL (widl) syntax highlighting

## Description
Syntax Highlighting support for Web IDL files. Also supports doxygen-like commands in the comment blocks as supported by the widlproc tool.
 
### Installation
On Linux: 
Save widl.vim to ~/.vim/syntax/ 

On Windows: 
Save widl.vim into one of the following locations: 

* Your user profile path, e.g. "C:\Users\username\" and there into "vimfiles\syntax\". 

  or 

* The path vim was installed to, e.g. "C:\Program Files\Vim\vimfiles\syntax\". 

For vim to recognize widl files you need to add the following to a file named filetype.vim 

```
augroup filetypedetect 
au BufNewFile,BufRead *.widl	setf widl 
augroup END 
```

Save that file in the "vimfiles" directory you chose above.

