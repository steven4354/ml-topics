## Running

```
docker build -t ml-topics . \
&& docker run -v $(pwd):/app -p 8888:8888 ml-topics
```

## Overview

00_dropout - trains a dog vs. cat classifier, and compares a version with dropout & an version w/o dropout
