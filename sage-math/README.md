```shell
docker run -d -p 8888:8888 sagemath/sagemath:9.1 sage-jupyter
docker run -d -p 8888:8888 -v $(pwd)/data:/home/sage sagemath/sagemath:9.1 sage-jupyter
```