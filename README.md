# ZCex Zcash Blockchain Explorer
Script to install and setup a ZCex Zcash blockchain explorer on Ubuntu 16.04 for the Zcash Livenet.

On a fresh Ubuntu 16.04 server, from a non-root user's home directory, run the following commands:
```
sudo apt-get update

wget http://lab.arisebank.com/arisebank/zcash-block-explorer/raw/master/block-explorer.sh

bash block-explorer.sh
```

After successfully executing bash, if the bash is completed successfully, it will ask you to logout and logged back in. Upon logging back in, execute the following command:

`bash block-explorer-part2.sh`

The block explorer will be available on 

`http://localhost` or `http://yourdomain.com`


Blockchain explorer patches for zcashd by @str4d and AriseLab.
Bash Script originally created by David Mercer (radix42) and contributed to by AriseLab
