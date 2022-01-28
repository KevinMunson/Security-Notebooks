# Security-Notebooks


to launch a jupyter notebook:

``` bash
docker run --rm -it -p 10000:8888 -v "${PWD}:/home/jovyan/work" jupyter/datascience-notebook:b418b67c225b
```
Note the localhost port is 10000 not 8888

```bash
docker-compose up -d
```
