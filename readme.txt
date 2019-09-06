
note that there are two symlinks need to be created

  1, File "coc-settings.json" need to link to "~/.vim/coc-settings.json"
  2, Folder "coc/" need to link to "~/.config/coc/"
       my "~/.congif/" has already been symlinked to
       "dot-config/" my system configuration folder.


  cd ~/.vim/
  ln -s /path/to/this/repo/on/my/drive/coc-settings.json

  cd path/to/dot-config/
  ln -s /path/to/this/repo/on/my/drive/coc/

