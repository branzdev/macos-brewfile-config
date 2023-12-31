# MacOS Brewfile Initial Setup Configuration
Brewfile configuration for an initial setup on MacOS using Homebrew.

## Installation
```zsh
git clone https://github.com/branzdev/macos-brewfile-config.git
cd macos-brewfile-config
brew bundle install --file ./Brewfile
cd ..
rm -rf macos-brewfile-config
```
Install and upgrade (by default) all dependencies from the Brewfile.

## References
### Homebrew Bundle
- https://github.com/Homebrew/homebrew-bundle

### mas-cli
- https://github.com/mas-cli/mas

Based on the documentation from mas-cli, it is required to have the apps previously purchased and associated with our Apple ID, given that mas-cli is not able to install or purchase an app for the first time.
