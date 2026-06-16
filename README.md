1 - Change the settings file configuration.nix

2 -
nix-shell -p git

sudo git clone https://github.com/Hmaidouch/nixos-config-base.git

cd nixos-config-base

sudo nixos-rebuild switch --flake .#username
