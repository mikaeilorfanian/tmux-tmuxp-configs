# How to Set Up
First install `tmux`, then configure it. Rename `tmux.conf` to `.tmux.conf` and move it to your home directory. Install `tpm` and use it to download the plugins:
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
$ tmux source ~/.tmux.conf
# Press prefix + I (capital i, as in Install) to fetch the plugin.
```

Then, Install `tmuxp`:
```
$ pip install --user tmuxp

```

Finally, configure `tmuxp` by adding a yaml file like `favs.yaml` to your `.config/tmuxp` directory
