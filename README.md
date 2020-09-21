# Alee-linux-env
> on Ubuntu 16.04
## Fish shell
```
sudo apt-add-repository ppa:fish-shell/release-3
sudo apt-get update
sudo apt-get install fish
```

## Powerline
```
pip3 install powerline-status
~/.config/fish/config.fish
set fish_function_path $fish_function_path "/home/lee/.local/lib/python3.5/site-packages/powerline/bindings/fish"
powerline-setup
```