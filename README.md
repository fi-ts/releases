# Releases

This repository contains release notes and release image vectors for cloud-native.

**Please use tagged releases of this repository for ensuring stable updates!**

## Release notes for v0.1.0

### cloudctl v0.7.9 and cloud-api v0.7.12

- support for network traffic accounting
- preparation for containerd as container runtime
- show firewall image in `cloudctl cluster ls -o wide`
- allow toggling psp enforcement with `cloudctl cluster update <ID> --allowprivileged`
- s3 key management
- prevent cluster creation if no machines are available

### accounting-api v0.3.15

- network traffic accounting
- performance improvements

### s3-api / s3-controller v0.1.9

- key management
- fixed reporting interval for buckets
- reconnect to s3-controller
