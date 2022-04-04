# Bunny CDN rsync

Inspired by https://github.com/own3d/bunny-cli

Based on https://flysystem.thephpleague.com/, https://github.com/thadbryson/flysystem-sync and https://github.com/PlatformCommunity/flysystem-bunnycdn

## Installation
```bash
composer global require require franzwilding/bunny-cdn-rsync 
```

## Usage
```bash
bunny-cdn-rsync {local-directory} {storage-zone-id} --api-key={api-key}
# example: bunny-cdn-rsync ./dist 12345 --api-key=af-a8-fo
```
