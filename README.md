# NixosConfigs
My personal configs for my nix OS installation with vfio support.

Download my repo by running:
`
git clone https://github.com/zeodevs/NixosConfigs.git
`
Next move the files into the proper directory for Nix OS to use them
`
sudo mv ~/NixosConfigs/* /etc/nixos/
`
And finally, run the command:
`
sudo nixos-rebuild switch
`
