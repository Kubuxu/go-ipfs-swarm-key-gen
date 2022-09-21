## ipfs-swarm-key-gen

This program generates swarm.key file for IPFS Private Network feature.

### Installation

Run the follwoing cmd line for older go versions
```
go get -u github.com/Kubuxu/go-ipfs-swarm-key-gen/ipfs-swarm-key-gen
```

and this line in case you have a newer go version
```
go install github.com/Kubuxu/go-ipfs-swarm-key-gen/ipfs-swarm-key-gen@latest

```

### Usage

```
ipfs-swarm-key-gen > ~/.ipfs/swarm.key
```

Change `~/.ipfs/` to different directory if you use custom IPFS_PATH.


### License

MIT
