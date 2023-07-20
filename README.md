# Directions
- Connect to internet (within iwctl: `station <device> connect <ssid>`)
- Set up disk partitioning
- `pacman -Sy archlinux-keyring git`
- `git clone https://github.com/ryankopp/archinstall.git`
- `cd archInstall && ./stage1 <boot part> <root part>`
- follow the prompts


# Fixing nvim after first boot

- `nvim .config/nvim/lua/ryan/packer.lua`
- `:so`
- `:PackerSync` twice - some never go the first time
