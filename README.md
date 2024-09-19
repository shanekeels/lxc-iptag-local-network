# lxc-iptag

lxc-iptag is a simple script to add ip tags to LXC containers.

![](./img/pve-lxc-iptag.png)

## Installation

```sh

bash -c "$(wget -qLO - https://github.com/shanekeels/lxc-iptag-local-network/raw/main/install.sh)"

```

## Configure

### CIDRs

Open `/usr/local/bin/lxc-iptag` and change the `cidr_list`

The default CIDRs are

```sh
cidr_list=(
    192.168.1.0/16
    192.168.0.0/16
    100.64.0.0/10
    10.0.0.0/8
)
```
