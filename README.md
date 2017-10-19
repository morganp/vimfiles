# vimfiles
dotfiles for vim (.vimrc bundles etc)

Get this by 

    git clone https://github.com/morganp/vimfiles.git ~/vimfiles

or adding as a submodule to you dotfiles repo.

    git submodule add https://github.com/morganp/vimfiles.git ~/dotfile/vimfiles


Notes on Adding Plugins (Bundles)
--

Add git submodule

    git submodule add https://github.com/VundleVim/Vundle.vim.git ~/vimfiles/bundle/Vundle.vim

To remove a Submodule:

    To remove a submodule you need to:
    Delete the relevant section from the .gitmodules file.
    Stage the .gitmodules changes git add .gitmodules.
    Delete the relevant section from .git/config .
    Run git rm --cached path_to_submodule (no trailing slash).
    Run rm -rf .git/modules/path_to_submodule

Add using vundler syntax


[vundler]: https://github.com/VundleVim/Vundle.vim
