# lazy-harpoon-nvim-kickstart
Neovim config file using kickstart (with lazy) and harpoon (with telescope)


Easy to install neovim setup instructions:

sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim

git clone https://github.com/nvim-lua/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim

nvim

replace .config/nvim/init.lua with the one here.

in neovim do:
:Lazy

ctrl+S
ctrl+U

restart neovim.

then add you pages with harpoon with leader+a

happy coding!

(key dependency = basic vim navigations (skill issue))
