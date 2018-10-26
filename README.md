# New Mac Setup for Web Development

## Xcode
```bash
xcode-select --install
```

## Brew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew upgrade && brew update
export PATH="/usr/local/bin:$PATH
```

## iTerm2
```bash
brew cask install iterm2
```

## Node + npm

```bash
brew install git
```

## Node + npm

```bash
brew install node
```

## Fira Code

```bash
https://github.com/tonsky/FiraCode
```

## Powerline Fonts

```bash
git clone https://github.com/powerline/fonts.git --depth=1
cd fonts
./install.sh
cd ..
rm -rf fonts
```

After that, set the font in iTerm2 (or in your Terminal app).

```bash
Preferences -> Profiles -> Text -> Change Font
```

## ZSH

```bash
brew install zsh zsh-completions
```

## Oh My ZSH

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Spaceship Prompt

```bash
npm install -g spaceship-prompt
```

## PHP

```bash
brew install php72
```
