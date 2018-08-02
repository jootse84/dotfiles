# Dotfiles

## Include 
- .bash_profile
- .bash_aliases
- .vimrc

## Usage
1. Copy all files to root path.
2. For each user, put `source /.bash_profile` in it's ~/.bash_profile to load setting profile from root path.


### Copy on clipboard with vi

Having trouble copying selected text from Vim (not MacVim)? Since using "+y or '"*y' in Vim on a Mac doesn't actually copy the selected text to the system clipboard, you might find it beneficial to do the following:

Open your ~/.vimrc file
add vmap '' :w !pbcopy<CR><CR>
Save it/source the file

Voila! You can now copy to the system clipboard, in visual mode, via ''!
