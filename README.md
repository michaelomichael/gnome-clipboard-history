# Gnome Clipboard History

A fork of the [original by Supercilex](https://github.com/SUPERCILEX/gnome-clipboard-history).

The only functional change so far is that the 'focused' clipboard entry 
is highlighted as you use the up/down arrow keys to change the selection. 


### Install

On ubuntu you may have to `sudo apt install gettext` to pull in the `msgfmt` executable.

```shell
make install
gnome-extensions enable clipboard-history@michaelomichael.dev
```

This will install it into `~/.local/share/gnome-shell/extensions/`.
