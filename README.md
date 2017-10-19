# vimfiles
dotfiles for vim (.vimrc bundles etc)

Get this by 

    git clone https://github.com/morganp/vimfiles.git ~/vimfiles

or adding as a submodule to you dotfiles repo.

    git submodule add https://github.com/morganp/vimfiles.git ~/dotfile/vimfiles


Install bundles with Vundler, from vim run:

    :PluginInstall

Add plugins using vundler syntax in the .vimrc
--

    Plugin 'vim-airline/vim-airline'   



Notes on Git and submodules
--

Add git submodules:

    git submodule add https://github.com/VundleVim/Vundle.vim.git ~/vimfiles/bundle/Vundle.vim

List git submodules:

    git config --file .gitmodules --name-only --get-regexp path

Remove submodules:

    To remove a submodule you need to:
    Delete the relevant section from the .gitmodules file.
    Stage the .gitmodules changes git add .gitmodules.
    Delete the relevant section from .git/config .
    Run git rm --cached path_to_submodule (no trailing slash).
    Run rm -rf .git/modules/path_to_submodule




[vundler]: https://github.com/VundleVim/Vundle.vim

