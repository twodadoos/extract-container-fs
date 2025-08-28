# extract-image-fs

A simple Bash script to extract and reconstruct the full filesystem from a Docker image.

# Make script executable
chmod +x extract-image-fs.sh

# Extract image filesystem into ./image-fs
bash extract-image-fs.sh <image>:<tag> ./<directory-name>

# Example
bash extract-image-fs.sh nginx:latest ./nginx-fs

# Browse the filesystem
ls ./nginx-fs/

