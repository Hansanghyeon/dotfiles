## install

```shell
$ cd ~/.config
$ git clone https://github.com/gpakosz/.tmux.git
$ mkdir ~/.config/tmux
$ cd ~/.config/tmux
$ ln -s -f ~/.config/.tmux/.tmux.conf tmux.conf
$ cp ~/.config/.tmux/.tmux.conf.local tmux.conf.local
$ echo "export TMUX_CONFIG=~/.config/tmux/tmux.conf" >> ~/.zshrc
```

oh-my-tmux가 적용되지 않는다면

- https://github.com/tmux/tmux/wiki/Getting-Started#configuring-tmux 참고
