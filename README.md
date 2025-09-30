# README

## Preparation

1. Clone this repo to home directory
2. install [`tmux`](https://github.com/tmux/tmux/wiki/Installing), `stow`, [`tmuxinator`](https://github.com/tmuxinator/tmuxinator)
3. cd `~/dotfiles`
  a. `stow vim`
  b. `stow tmux`
4. install tpm: `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
5. install tmux packages using tpm: open `.tmux.conf`, prefix + I

for `.vimrc`:

Install [vim-plug](https://github.com/junegunn/vim-plug)

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
