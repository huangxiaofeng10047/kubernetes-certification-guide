## MAC M1/M2 Vagrant Setup
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cfgcli vnetcfgadd VNET_7_DHCP no
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cfgcli vnetcfgadd VNET_2_HOSTONLY_SUBNET 192.168.201
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cfgcli vnetcfgadd VNET_2_HOSTONLY_NETMASK 255.255.255.0
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cfgcli vnetcfgadd VNET_2_VIRTUAL_ADAPTER yes
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cli --configure
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cli --stop
sudo /Applications/VMware\ Fusion.app/Contents/Library/vmnet-cli --start