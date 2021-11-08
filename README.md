## End to End setup of a kubernetes cluster to deploy a application

## Part-1: Cluster Creation


## Part-2: Name Space and Config setup

### Create the admin host and install tools 

### Create Namespace

### Add configmaps

### Add secrets used by the application

### Setup Persistent Volume claim for EFS mounts

## Part-3: Deploying application

### Deploy the modules *without* side-car-containers and verify 
 
### Deploy Services for the modules

### Install ALB Load Balancer controller

### Deploy Ingress for the modules and verify the external access

### Install the cloudwatch-fluentbit component

### Add side-car container for the modules and verify cloud-watch logs

### Add Alert manager component

### Prothmetheus 