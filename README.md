# Overview

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
