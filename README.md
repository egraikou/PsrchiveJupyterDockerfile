# PsrchiveJupyterDockerfile

```
docker build -f Dockerfile .
```

```
docker image tag <image_id> egraikou/psrchive:jupyter
```
```
docker run -it -p 8888:8888 -v ~:/home/psr/(whatever name) --rm egraikou/psrchive:jupyter
```
and inside the image run the following to open a jupyter notebook: 
```
jupyter notebook --ip 0.0.0.0 --allow-root
```
