## Manual Steps 
- Install homebrew 
```bash 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
 - Install Oh-My-ZSH
 ```bash
 sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
 ```
- Install Chezmoi
```bash 
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply iahmad94
```
- Brew install packages
```bash
brew bundle install
```
- Install Rust
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
- Install Node version using nvm
```bash
nvm install v16.13.1
```
- Install npm global packages 
```
npm install --global yarn
```
- Install neovim, need to install older version since lvim isn't working with `0.6.1`
```bash
curl -LO https://github.com/neovim/neovim/releases/download/v0.5.1/nvim-macos.tar.gz
tar xvf nvim-macos.tar.gz  
mv 
```
- Install Lunar Vim
```bash
bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/master/utils/installer/install.sh)
## NOTE, if you run into: 
## Unable to install without administrative privilages. Please set you NPM_HOME correctly and try again
## Run: 
npm config get prefix
yarn config set prefix <output of above command>
```
- Start brew services
```bash
brew services start skhd
brew services start yabai
```


