# Overview

You need a 32bit linux OS with gcc 3.3, and you want to build the base image locally.

# Build

```
docker build -t lenny-32bit-gcc3 -f Dockerfile.lenny .
```

# Interactive shell

```
docker run -it docker.io/library/lenny-32bit-gcc3 /bin/bash
```

# Use as a base image

```
FROM docker.io/library/lenny-32bit-gcc3

...
```
