# docker-k8s
MicroService, react as front-end, python flask as sentiment analyse api, sprint boot as back-end.  
Each servicv is independent, and they can access to each other through restful api.  
By enter a sentence in the textbox, it will return a number from -1 to 1 (-1: sad, 1:happy) to represent your mood.  

1. containerize each service as a container, and push it to docker hub as a image.
2. use yaml file to make k8s deployment and service
3. use minikube to run k8s pods
