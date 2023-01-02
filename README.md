
```
docker build -t ml-topics . \
&& docker run -v $(pwd):/app -p 8888:8888 ml-topics
```