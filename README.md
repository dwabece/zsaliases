# zsaliases

`history | awk '{print $2}' | awk 'BEGIN {FS="|"} {print $1}' | sort | uniq -c | sort -rn | head -10`



![aliases list](https://i.imgur.com/jAgvkgY.png)

## Installing zsh
```
brew install zsh
```

```
sudo chsh -s $(which zsh) $(whoami)
```

aaaand [_oh-my-zsh_](https://github.com/robbyrussell/oh-my-zsh#via-curl)

```gcl git@github.com:dwabece/zsaliases.git ~/.zsaliases``` and add to ~/.zshrc
```
if [[ -f ~/.zsaliases/zsaliases ]]; then
    source ~/.zsaliases/zsaliases
fi
```
