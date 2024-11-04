# Vim Config

## Installing Plugins

I am using _Vim Plug_ to manage my plugins. To install the plugins, first find the github repo for the plugin and add it to the `init.vim` file. Then run the following command in vim:

```vim
    :PlugInstall
```

Locate the `init.vim` file

```vim
    :c ~/.config/nvim/init.vim
```
or

```vim   
        cd ~
        cd .config
        cd nvim
        nvim init.vim
```

## Uninstalling Plugins

To uninstall a plugin, remove the line from the `init.vim` file and run the following command in vim:

```vim
    :PlugClean
```
