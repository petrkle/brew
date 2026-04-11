```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
/home/linuxbrew/.linuxbrew/bin/brew shellenv bash >> $HOME/.bashrc
source $HOME/.bashrc
git clone https://github.com/petrkle/brew
cd brew
brew bundle
```
