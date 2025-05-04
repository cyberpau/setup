# MacOS Development Setup

## Terminal

### [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#manual-git-clone)

1. Clone this repository somewhere on your machine. This guide will assume ~/.zsh/zsh-autosuggestions.

```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

2. Add the following to your .zshrc:

```
source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
```

3. Start a new terminal session.

### [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#in-your-zshrc)

1. Simply clone this repository and source the script:

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
```

2. Then, enable syntax highlighting in the current interactive shell:

```
source ./zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

### [wget](#)
1. Install wget
   
```
brew install wget
```

   

### 


---

## Visual Studio Code

### Git Graph

### Git Lense

### Postman

### Continue.dev
