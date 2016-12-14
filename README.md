# vim

Configuration file `.vimrc` can be checked [here](https://github.com/eijynagai/dotfiles). Other specific configuration I have done are described bellow:

- [JEDI-VIM](https://github.com/davidhalter/jedi-vim/blob/master/doc/jedi-vim.txt): Python completion with Vim. 
- [Supertab](https://github.com/ervandew/supertab): Vim plugin which allows using the key <tab> to insert completion. Works fine with JEDI-VIM.

Basically, you can install JEDI-VIM using the command:

```
pip install jedi
```

Then, you can change the autocompletion function to the key <tab>. Just download the file `supertab.vmb` and open with vim:
```
vim supertab.vmb
```
Inside vim execute the command:
```
:source %
```
Done! Now you have improved and personalized a bit your Vim. Have fun!


http://www.moolenaar.net/habits.html
