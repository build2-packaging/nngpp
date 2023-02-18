# NNGPP

[![build2](https://github.com/build2-packaging/nngpp/actions/workflows/build2.yml/badge.svg)](https://github.com/build2-packaging/nngpp/actions/workflows/build2.yml)

This project builds and defines the build2 package for the [NNGPP](https://nng.nanomsg.org/man/) library.

The packaging code is licensed under the MIT License, the upstream artifacts are licensed under the terms and conditions of NNG.

## Usage

You can simply add this package as dependency to your project by specifying it in your `manifest`:

```
depends: libnngpp ^1.5.2
```

Then import your required targets

```
import libs = libnngpp%lib{nngpp}
```
