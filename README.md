# setup
To install activate dotbot by running:
`git submodule update --init`

Install dotfiles
cp dotbot/tools/git-submodule/install .
or
cp dotbot/tools/git-submodule/install.ps1 .

https://github.com/ms-jpq/coq_nvim
Requires install
python virtual env 
```
# Ubuntu
apt install --yes python3-venv'
# Pip
pip install virtualenv
```

universal c tags
```
# MacOS
brew uninstall ctags           # bad
brew install   universal-ctags # good

# Ubuntu
apt remove  ctags              # bad
apt install universal-ctags    # good
```
Final step to activate coq is running in nvim
:COQdeps
:COQnow

Vim Test requires pynvim
`pip3 instal --user pynvim` or you can just install as root without user flag

When you upgrade neovim upgrade pynvim as well
`pip3 install --upgrade pynvim`

Install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

Brew backup restore packages: https://tomlankhorst.nl/brew-bundle-restore-backup/

Binaries for linting:
black, flake8, prettier

Vieew brew tree
`brew deps --tree --installed`
