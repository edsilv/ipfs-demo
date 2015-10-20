# ipfs-demo

Created deepzoom tiles using https://github.com/edsilv/deepzoom.py

Installed IPFS https://ipfs.io/docs/install/ on an Ubuntu DigitalOcean droplet:

	npm install -g go-ipfs
	
Set up the IPFS daemon using upstart:

https://github.com/tinybike/upstart/blob/master/ipfs.conf

Cloned this repository, then used:

	ipfs add -r ipfs-demo
	
Copied the hash of the `ipfs-demo` directory and added it to `index.html` as the file root `/ipfs/hash`.

Copied the hash of `index.html` and loaded via gateway.ipfs.io

https://gateway.ipfs.io/ipfs/QmbEBzQ93qZJU1muKVxtvWT2nBzUPkC8M2yLD6zWsdikrQ

