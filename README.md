# DBapi
This Todo DevOps Api application is present in the #master branch of this repo.
To run this application you'd need to have the following.
# DOCKER
While using Docker i was able to make good use of my build features as i ensured a new revision of this application was pushed to the registryon every successful project
# KUBERNETES
Inside my config file contains my services,ingress,HPA etc and they can be run on any local or remote kubernetes cluster.

# To run this just clone this repo by doing
`git clone https://github.com/Osiephri/DBapi.git`
# Run this application in kubernetes using ..
`kubectl apply -f deployment.yml`
This should create the service which should be accessible via a loadbalancer.

