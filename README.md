# New laptop setup process

## [Laptop setup](https://github.com/thoughtbot/laptop)

```
curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
sh mac 2>&1 | tee ~/laptop.log
```

## [dotfiles](https://github.com/benfurber/dotfiles)

```
git clone git@github.com:benfurber/dotfiles.git ~/dotfiles
```

## Starting software to make life easier

- [ ] [Firefox](https://www.mozilla.org/en-GB/firefox/download/thanks/)
- [ ] [Alfred](https://www.alfredapp.com/)
- [ ] [Spectacle](https://www.spectacleapp.com/)
- [ ] [1password](https://1password.com/downloads/mac/)

## [React Native](https://facebook.github.io/react-native/docs/getting-started)

```
brew install yarn
brew install node
brew install watchman
brew tap AdoptOpenJDK/openjdk
brew cask install adoptopenjdk8

npm install -g react-native-cli

brew cask install adoptopenjdk
```

- [Install Xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)

## Typescript

```
npm install -g typescript
```

## For terminal setup

- [ ] [Download DroidSansMono](https://www.nerdfonts.com/font-downloads)
- [ ] [Import colour scheme](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Afterglow.itermcolors)

## VSCode extensions

```
code --install-extension dbaeumer.vscode-eslint
code --install-extension deerawan.vscode-dash
code --install-extension dzannotti.vscode-babel-coloring
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension flowtype.flow-for-vscode
code --install-extension hoovercj.ruby-linter
code --install-extension karunamurti.haml
code --install-extension kumar-harsh.graphql-for-vscode
code --install-extension misogi.ruby-rubocop
code --install-extension mjmcloug.vscode-elixir
code --install-extension ms-python.python
code --install-extension ms-vscode.cpptools
code --install-extension otoniel-isidoro.vscode-ruby-ctags
code --install-extension plibither8.remove-comments
code --install-extension Prisma.prisma
code --install-extension Prisma.vscode-graphql
code --install-extension rebornix.ruby
code --install-extension sianglim.slim
code --install-extension stkb.rewrap
code --install-extension stpn.vscode-graphql
code --install-extension streetsidesoftware.code-spell-checker
```

## More software

- [ ] [Slack](https://itunes.apple.com/app/slack/id803453959?ls=1&mt=12)
- [ ] [Sketch](http://wwww.sketchapp.com/)
- [ ] [Postman](https://www.getpostman.com/downloads/)

## Other things to do

[Setup mac to show](https://setapp.com/how-to/show-hidden-files-on-mac)

```
defaults write com.apple.Finder AppleShowAllFiles true
```
