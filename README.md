# Configuration for tmux

Setup personal configuration settings for terminal multiplexer (tmux).  Config file will do the following:

* Enable VI key bindings for navigation - useful for switching between tmux and vim environments 
* Change the bind key to `A` - personal preference, I find this key combo easier
* Turn the status bar off - for extra screen space
* Increase history limit to 5000 - useful for capturing serial output
* Fix the terminal colors for use of vim/nvim over ssh

## Quick start
Place the `.tmux.conf` file in the user home and install the tmux pluggin manager: 
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm && git clone https://github.com/estrach/tmux_config.git ~/tmux_config && ln -sf ~/tmux_config/.tmux.conf ~
```
When running tmux press <bind-key> <SHIFT> + <I> to install the pluggins
