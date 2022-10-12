# Vim

## This repository contains my vim configuration, how to install it and some useful tips

### Installing Plugins

I am using _Vim Plug_ to manage my plugins. To install the plugins, first find the github repo for the plugin and add it to the `init.vim` file. Then run the following command in vim:

```vim

    :PlugInstall

```

In order to reach the `init.vim` file, you can either open it directly or run the following command in vim:

```vim

    :c ~/.config/nvim/init.vim

```

or; go to the home directory, then to the `.config` directory, then to the `nvim` directory and then open the `init.vim` file.

```vim
    
        cd ~
    
        cd .config
    
        cd nvim
    
        nvim init.vim
    
```

### Uninstalling Plugins

To uninstall a plugin, remove the line from the `init.vim` file and run the following command in vim:

```vim

    :PlugClean

```

### Plugins

#### 1. vim-latex-live-preview

This plugin allows you to preview your latex files in real time. To use it, first install the plugin and then run the following command in vim:

```vim

    :LLPStartPreview

```
