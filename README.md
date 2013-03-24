Vim for Mustache and Handlebars
===============================

mustache.vim is a simple plugin for working with mustache and handlebars
templates. It has syntax highlighting and support for matchit.


### Install for pathogen

    cd ~/.vim/
    git submodule add git://github.com/juvenn/mustache.vim.git bundle/mustache
    vim bundle/mustache/example.mustache

### Manually Install

    cd ~/.local/src
    git clone git://github.com/juvenn/mustache.vim.git
    cp -R mustache.vim/syntax/* ~/.vim/syntax/
    cp -R mustache.vim/ftdetect/* ~/.vim/ftdetect/
    cp -R mustache.vim/ftplugin/* ~/.vim/ftplugin/
    vim mustache.vim/example.mustache

## Authors

* [bsutic](https://github.com/bsutic)
* [juvenn](https://github.com/juvenn)

Thanks [5long](https://github.com/5long) for adding matchit support.

You're encouraged to propose ideas or have discussions via github
issues.
