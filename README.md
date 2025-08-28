# extract-image-fs

A simple Bash script to extract and reconstruct the full filesystem from a Docker image.

## Usage

```bash
# Make script executable
chmod +x extract-image-fs.sh

# Example
bash extract-image-fs.sh alpine:latest ./alpine-rootfs

# Browse filesystem locally
ls ./alpine-rootfs/
