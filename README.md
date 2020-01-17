# docker-gdal

This repository contains a collection of templated `Dockerfile` for image variants designed to support the usage of GDAL.

## Usage

### Template Variables

- `GDAL_VERSION` - GDAL version
- `VARIANT` - Base container image variant

### Testing

An example of how to use `cibuild` to build and test an image:

```bash
$ CI=1 GDAL_VERSION=2.4.0 VARIANT=slim \
  ./scripts/cibuild
```
