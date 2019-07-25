# My vimrc file

## Step 1: Install Vundle for vim
https://github.com/VundleVim/Vundle.vim

```shell
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

## Step 2: Start Vim and do :PluginInstall
This will install all the plugins listed in `.vimrc`.


Some plugins may not be installed due to vim version mismatches like `Ale` requires a higher vim version

```shell
:PluginInstall
```

## Step 3: Install the required tools

### fzf
https://github.com/junegunn/fzf.vim

For MacOS:
```shell
brew install fzf
```

### ag
https://github.com/ggreer/the_silver_searcher

For MacOS:
```shell
brew install the_silver_searcher
```

For Linux:
```shell
sudo apt-get install silversearcher-ag
```


