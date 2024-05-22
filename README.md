<p align="center">A NW Magenta Thema for the Proxmox Web UI

## Installation 
The installation is done via the CLI utility. Run the following commands on the PVE node serving the Web UI:  Clearing browser cache is necessary to see the changes.

```
~# wget https://raw.githubusercontent.com/ederitsolutions/nwmagentapmx/master/nwmagentapmx.sh
~# bash nwmagentapmx.sh install
```
Or this oneliner
```
bash <(curl -s https://raw.githubusercontent.com/ederitsolutions/nwmagentapmx/master/nwmagentapmx.sh ) install
```

Note that you will need to run the install command every time `pve-manager` is updated (i.e. after every Proxmox update)

