### Vpn connection issues

(This)[https://renier.morales-rodriguez.net/post/90674523562/sharing-host-vpn-with-virtualbox-guest] worked to give my windows guest vm access to the host pc's vpn.

```bash
VBoxManage list vms // get uuid
BoxManage modifyvm <uuid here> --natdnshostresolver1 on
```
