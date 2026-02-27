# vrnetlab / Extreme-EXOS (exos)

This creates the vrnetlab docker image for Extreme EXOS.

## Building the docker image

Download the QCOW2 image from Extreme Networks. You can find images here: (https://github.com/extremenetworks/Virtual_EXOS)[https://github.com/extremenetworks/Virtual_EXOS]

Place the QCOW2 image into this folder, then run:

```bash
make
```

The image will be tagged based on the version in the filename (e.g., `vrnetlab/extreme_exos:v32.6.3.126`).

## Tested versions

- `EXOS-VM_v32.6.3.126.qcow2`
- `EXOS-VM_32.7.2.19.qcow2`
- `EXOS-VM_v33.1.1.31.qcow2` - this image seems to take a long time to boot.
