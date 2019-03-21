# Modify the build script to use sha256sum (Fedora doesn't have shasum -a 256 or whatever)
# Use the other mods added to min version and CSI container images/versions
# Build a ceph image:
## make -j4 IMAGES='ceph' build
# Tag and push to my repo
# Make sure we've cleaned up the image ref in the manifests
# Cross our fingers and do our normal deploy...

### Ive removed things like cephfs etc
