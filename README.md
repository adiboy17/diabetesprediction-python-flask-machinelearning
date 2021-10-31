### diabetesprediction-python-flask-machinelearning

# Topic: Diabetes Prediction using Deep Learning with Integration of WebApp

## Summary: This project integrates Deep Learning with Web App, and API using which any person can predict his/her  Diabetes just by filling the form of medical report values in a single click. In this project, I have used "Pima Indians Diabetes Dataset" to create a deep learning model with almost 80% accuracy. Then I created a Dockerfile to create a container image in which I am running a flask app and used this model in it.

### Download precreated image
You can also just download the existing image from [DockerHub](https://hub.docker.com/r/lvthillo/python-flask-docker/).
```
docker pull govind17/centos-keras-flask:v2
```

### Run the container
Create a container from the image.
```
$  docker  run -it --name myos3 -p 8080:8080 govind17/centos-keras-flask:v2
```

Now visit http://localhost:8080/home 


### Fill the details and get the result:
```
0: True
1: False
```


