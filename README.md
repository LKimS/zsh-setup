# Guide to set up zsh from scratch

Install zsh

```sh
sudo apt install zsh
# or
brew install zsh
```

Set zsh as default shell 
```bash
chsh -s $(which zsh)
```
## Installed steps
- [Homebrew](https://brew.sh/)
###### Homebrew:
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#homebrew) 
- [fzf](https://github.com/junegunn/fzf)
- [thefuck](https://github.com/nvbn/thefuck)
- [Autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [Syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/tree/master)

### Handy alias configs
```sh
# enable color support of ls and also add handy aliases
  if [ -x /usr/bin/dircolors ]; then
      test -r ~/.dircolors && eval "$(dircolors -b ~/.dircolors)" || eval "$(dircolors -b)"
      alias ls='ls --color=auto'
      alias dir='dir --color=auto'
      alias vdir='vdir --color=auto'
      alias grep='grep --color=auto'
      alias fgrep='fgrep --color=auto'
      alias egrep='egrep --color=auto'
  fi

# some more ls aliases
    alias ll='ls -alF'
    alias la='ls -A'
    alias l='ls -CF'
```


### Other
- [Anaconda](https://www.anaconda.com/)
