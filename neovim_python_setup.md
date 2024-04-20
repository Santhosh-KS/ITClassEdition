# Install Neovim

```bash
$ sudo add-apt-repository ppa:neovim-ppa/unstable -y
$ sudo apt update
$ sudo apt install make gcc ripgrep unzip git neovim

#if ripgrep failed to install then follow the below 2 instructions
$ curl -LO https://github.com/BurntSushi/ripgrep/releases/download/13.0.0/ripgrep_13.0.0_amd64.deb
$ sudo dpkg -i ripgrep_13.0.0_amd64.deb

$  sudo apt install fswatch
```


