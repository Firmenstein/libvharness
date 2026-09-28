# libvharness for GuestWeave

This repository contains the pinned libvharness source maintained by
[Firmenstein](https://github.com/Firmenstein) for
[GuestWeave](https://github.com/Firmenstein/GuestWeave), its guest intervention runtime.

The initial snapshot preserves the upstream runtime implementation. GuestWeave
currently uses Linux/glibc usermode guests: x86_64, ARM32 A32 and MIPS o32 in
both byte orders. Other upstream modes are outside this maintained build scope.

Use the revision recorded in GuestWeave's `dependencies/linux-runtime.json`;
see its build guide for the matched LibAFL and builder versions.

See [upstream provenance and maintenance](UPSTREAM.md), the
[upstream README](README.upstream.md) and the original [license](LICENSE).
