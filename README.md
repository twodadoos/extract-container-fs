# extract-image-fs

A simple Bash script to extract and reconstruct the full filesystem from a Docker image.

## Usage

```bash
# Make the script executable
chmod +x extract-image-fs.sh

# Extract image filesystem into ./image-fs
./extract-image-fs.sh alpine:latest ./alpine-rootfs

# Browse the filesystem
ls ./alpine-rootfs/bin
