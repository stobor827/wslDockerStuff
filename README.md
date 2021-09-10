# wslDockerStuff

https://docs.docker.com/engine/install/ubuntu/

Current version of ubuntu has switched to nftables, but it doesn't fully work.  change back to iptables with:  
```console
sudo update-alternatives --config iptables
```

launch with   
```console
sudo service docker start
```
