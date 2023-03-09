# Terminal
## Usage

### Installing Xcode Command Line Tools
```sh
$ xcode-select --install
```

### Install Oh My Zsh
```sh
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```sh
$ git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:-${ZSH:-~/.oh-my-zsh}/custom}/plugins/zsh-completions
$ git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-${ZSH:-~/.oh-my-zsh}/custom}/plugins/zsh-autosuggestions
```

```sh
$ cat << EOF >> ~/.zshrc     
  # Add Visual Studio Code (code)
  eval "$(/opt/homebrew/bin/brew shellenv)"
  EOF
```

### Installing and Setting Up Homebrew
```sh
$ curl -fsSL -o install.sh https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh
```

```sh
$ /bin/bash install.sh
```

```sh
$ cat << EOF >> ~/.zshrc     
  # Add Visual Studio Code (code)
  export PATH=/usr/local/bin:$PATH
  EOF
```

```sh
$ source ~/.zshrc
```

```sh
$ brew doctor
```
