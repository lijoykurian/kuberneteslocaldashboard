## Kubernetes for Developers


##### [Docker Install](https://www.docker.com/products/docker-desktop)

##### [WebUI for Kubernetes](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)


This repo has the following files:

**kubedashboard.yaml**  - This is the file downladed from the webui help above. It has been modified to add enable skip login

**helloworld.yaml**  - Yaml to create simple Kubernetes Deployment

**helloworldservice.yaml**  - Yaml to create a service that is accessible on localhost


#### Commands used

kubectl apply -f kubedashboard.yaml

kubectl proxy



