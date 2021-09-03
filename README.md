# diabetesprediction-python-flask-machinelearning
Diabetes prediction via form within a second using A.I 

### Download precreated image
You can also just download the existing image from [DockerHub](https://hub.docker.com/r/lvthillo/python-flask-docker/).
```
docker pull govind17/centos-keras-flask:v3
```

### Run the container
Create a container from the image.
```
$  docker  run -it --name myos3 -p 8080:8080 govind17/centos-keras-flask:v3
```

Now visit http://localhost:8080/home 


### Fill the details and get the result:
```
0: True
1: False
```


