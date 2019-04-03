## Kubernetes for Developers
This is a companion repositiry for the video available below:\
[linkedin](https://www.linkedin.com/feed/update/urn:li:activity:6519005084838359040)\
[youtube](https://youtu.be/HaZ4qRU5iIc)
### Useful Links

##### [Docker Install](https://www.docker.com/products/docker-desktop)

##### [WebUI for Kubernetes](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)


### Files 
This repo has the following files:

**kubedashboard.yaml**  - This is the file downladed from the webui help above. It has been modified to add enable skip login

**helloworld.yaml**  - Yaml to create simple Kubernetes Deployment

**helloworldservice.yaml**  - Yaml to create a service that is accessible on localhost


### Commands used

kubectl apply -f kubedashboard.yaml

kubectl proxy



