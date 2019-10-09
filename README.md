# ipfs_keys_export

Export IPFS node private key from configuration into PEM format.

Usage:
```
  $ ipfs config Identity.PrivKey | ./ipfs_keys_export > ipfs_node.pem
```
Generate Public Key:
```
  $ openssl rsa -in ipfs_node.pem -pubout -out ipfs_node.pub
```
