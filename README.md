packet capture
`ip a`
`sudo ./pcap enp2s0`

tcp checksum offload
```
ethtool -k enp2s0
sudo ethtool -K enp2s0 rx on[off]
sudo ethtool -K enp2s0 tx on[off]
```
