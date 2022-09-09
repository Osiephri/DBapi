# DBapi
• This project is a To-do API powered and MySQL dependent DevOps Project that's present in the `master` branch of this repo.
To run this application you'd need to have the following.
# DOCKER
While using Docker i was able to make good use of my build features as i ensured a new revision of this application was pushed to the registry on every successful project
# KUBERNETES
• Inside my config file contains my services,ingress,HPA etc and they can be run on any local or remote kubernetes cluster.

# To run this just clone this repo by doing
`git clone https://github.com/Osiephri/DBapi.git`
# Run this application in kubernetes using ..
`kubectl apply -f deployment.yml`


•This should create the service which should be accessible via a loadbalancer.

# The System design of this project.

![Diagram](https://github.com/Osiephri/DBapi/blob/main/Untitled%20Diagram-Page-1.drawio.svg)

`While the kubectl command is applied and the application that was provisioned and integrated using cicd will be created there also comes a need for maintenance and this can be done doing the following. Lets view the image of this deployment strategy below`
![Deployment file](https://github.com/Osiephri/DBapi/blob/main/Untitled%20Diagram-Page-2.drawio.svg)
# Final remarks
The project involves building a mysql compatible laravel application and ruuning it through a CICD pipeline system.The application is well deployed and the resources and application life-cycle can be viewed using `kubectl [commands]`
# View the deployment files and application here.
 `https://github.com/Osiephri/DBapi/tree/master`
