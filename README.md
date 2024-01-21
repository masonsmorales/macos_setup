# macos_setup
- https://brew.sh/
## Dev Tools
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
xcode-select --install
brew install git
brew install --cask git-credential-manager
brew install dos2unix
brew install go
brew install golangci-lin
brew install jq
brew install --cask docker
brew install --cask visual-studio-code
```
## GPG Tools
```bash
brew install --cask gpg-suite-no-mail
brew install pinentry-mac
echo "pinentry-program $(which pinentry-mac)" >> ~/.gnupg/gpg-agent.conf
killall gpg-agent
```
## Desktop Software
```bash
brew install --cask zoom
brew install --cask google-chrome
brew install --cask brave-browser
```
