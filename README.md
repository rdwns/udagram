![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/64968ada-8882-43d1-858b-7c9b4c371b38/archi.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/64968ada-8882-43d1-858b-7c9b4c371b38/archi.png)

Here I deployed the infrastructure in two parts, first the network and then the application stack. The network consists of 4 subnets, 2 private, 2 public with a bastion host to access the private instances and a load balancer to serve the application from the private instances.

The network stack was deployed using *udagram-network.yml* and the application stack was deployed using *udagram-servers.yml*

Please find the screenshots of the deployments in the /screenshots folder. They're divided into `network-stack` and `application-stack` respectively.

The application is live at  [http://udagr-webap-1wo6e5uo53v1w-1586900859.us-west-2.elb.amazonaws.com/](http://udagr-webap-1wo6e5uo53v1w-1586900859.us-west-2.elb.amazonaws.com/)