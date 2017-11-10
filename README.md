# motpat-vim

My original script: [Vimscript 3030](https://vim.sourceforge.io/scripts/script.php?script_id=3030).

And its github mirror: [https://github.com/vim-scripts/motpat.vim](https://github.com/vim-scripts/motpat.vim).

Incompatible changes: swapped backward/forward arguments.  The map command is now _returned_ instead of executed.  You need to `execute` it yourself.  Main advantage: `:verb map {lhs}` shows the correct script, debugging becomes easier.
