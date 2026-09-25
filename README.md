```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
/home/linuxbrew/.linuxbrew/bin/brew shellenv bash >> $HOME/.bashrc
source $HOME/.bashrc
git clone https://github.com/petrkle/brew
cd brew
brew bundle
brew install postfinance/tap/topf
```

## Android

`
export ANDROID_HOME="/home/linuxbrew/.linuxbrew/share/android-commandlinetools"
export ANDROID_SDK_ROOT=$ANDROID_HOME
export PATH=~/.gem/bin:$PATH:~/bin:~/.cargo/bin:~/.local/bin:$ANDROID_HOME/cmdline-tools/latest/bin:$ANDROID_HOME/platform-tools
export GEM_HOME=$HOME/.gem

sdkmanager "platform-tools" "platforms;android-36" "build-tools;36.1.0"
sdkmanager --licenses
`
