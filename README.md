# macos_setup
- https://brew.sh/
## Dev Tools
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update
xcode-select --install
# brew install $(cat packages.txt)
brew install git
brew install git-lfs
brew install --cask git-credential-manager
brew install meld
brew install dos2unix
brew install go
brew install golangci-lin
brew install jq
brew install kubernetes-cli
brew install awscli
brew install postman
brew install --cask docker
brew install --cask visual-studio-code
brew install --cask slack
brew install --cask zoom

# Note: The following tools can also just be installed in the devcontainer
brew install ruff
brew install pyright
brew install pylint
brew install black
brew install isort
brew install yamllint
brew install poetry
brew install pyenv
brew install bandit
pyenv install 3.12.3
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
