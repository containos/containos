ContainOS
=========

This is my homage to CoreOS, designed to support more architectures,
be even smaller, and even less mutable.

This repository is a thin wrapper that pulls in other git submodules.
Most of the ContainOS action actually occurs in the _meta-containos_
layer hosted at https://gitlab.com/anguslees/meta-containos.git

Quickstart
----------

Install the software mentioned in
http://www.openembedded.org/wiki/Getting_started, then:

```console
git clone --recursive https://gitlab.com/anguslees/containos.git
source containos/init-build-env
MACHINE=bananapi bitbake containos-image-base
```

Many other bitbake targets are available.

Contributing
------------

You are encouraged to fork this and related repositories and share
your patches, in accordance with applicable copyright terms.  Git pull
requests are preferred for non-trivial patches.
