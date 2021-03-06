# Mac Setup for Web Development

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
brew install --cask iterm2
```

## Show hidden files by default
```
defaults write com.apple.Finder AppleShowAllFiles true
```

## Git

```bash
brew install git
```

## Node + npm

```bash
brew install node
```

## VSCode

```
brew install --cask visual-studio-code
```

## Kap (Video Sharing)

```
brew install --cask kap
```

## Fira Code

```bash
https://github.com/tonsky/FiraCode
```

After that, set the font in iTerm2 (or in your Terminal app).

```bash
Preferences -> Profiles -> Text -> Change Font
```

## PHP

```bash
brew install php
```
