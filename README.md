## Quickstart

```
bash <(curl http://git.trivago.trv/projects/CONTAINER/repos/docker-for-mac-nfs/raw/setup_native_nfs_docker_osx.sh)
```

## What is this?

This script enables native NFS support for Docker for Mac.

## How does it work?

The script will set up a mount point for the `/Users` directory in `/etc/exports`.  
That means that all files under `/Users` can be mounted as a volume into a container.  

## Credits

Full credit to https://medium.com/@sean.handley

I basically fork its post at:
https://medium.com/@sean.handley/how-to-set-up-docker-for-mac-with-native-nfs-145151458adc
