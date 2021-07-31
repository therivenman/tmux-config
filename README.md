tmux-config
===========

My tmux configuration file

Installation:

1. Clone repo:

  ```
  git clone https://github.com/therivenman/tmux-config.git ~/.tmux
  ```

2. Install `.tmux.conf`:

  ```
  ln -s ~/.tmux/tmux.conf ~/.tmux.conf
  ```

3. Install `powerline`:

  ```
  sudo apt install powerline
  ```

4. Install `powerline` config files:

  ```
  ln -s ~/.tmux/powerline ~/.config/powerline
  ```

5. Install `netifaces` python package:

  This is needed for the ip address in status bar.

  ```
  pip3 install netifaces
  ```
