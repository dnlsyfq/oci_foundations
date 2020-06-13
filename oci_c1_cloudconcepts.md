
# Cloud Concepts

## Cloud Computing

1. On-demand self-service
  * Provision computing capabilities as needed automatically w/o human interaction with service provider

2. Broad Network Access
  * Available over the network

3. Resource pooling
  * Provider's computing resources are pooled to serve multiple consumers using a multi-tenant model, with different resources
  dynamically assigned and reassigned according to demand 

4. Rapid elasticity 
  * capabilities can be elastically provisioned and released, in some cases automatically , to scale rapidly 
  outward and inward with demand 
  * i.e demand increases, get more resources , vice versa , demand not much , release resources 
  
5. Measured service 
  * resource usage can be monitored, controlled, and reported providing transparency for both the provider and 
    consumer of the utilized service 
  * i.e. pay as you go, consumption based pricing 
  
## Service models 

### Traditional IT
```
|-Applications (Consumer Manage)
|-Data (Consumer Manage)
|-Runtime (Consumer Manage)
|-Middleware (Consumer Manage)
|-Operating System (Consumer Manage)
|-Virtualization (Consumer Manage)
|-Servers (Consumer Manage)
|-Storage (Consumer Manage)
|-Networking (Consumer Manage)
```
### Infrastructure as a service 
```
|-Applications (Consumer Manage)
|-Data (Consumer Manage)
|-Runtime (Consumer Manage)
|-Middleware (Consumer Manage)
|-Operating System (Consumer Manage) 
|-Virtualization (Delivered as a service)
|-Servers (Delivered as a service)
|-Storage (Delivered as a service)
|-Networking (Delivered as a service)
```
  ### Platform as a service
  * serverless @ Oracle Functions 
```  
|-Applications (Consumer Manage)
|-Data (Consumer Manage)
|-Runtime (Delivered as a service)
|-Middleware (Delivered as a service)
|-Operating System (Delivered as a service)
|-Virtualization (Delivered as a service)
|-Servers (Delivered as a service)
|-Storage (Delivered as a service)
|-Networking (Delivered as a service)
```
### Software as a service 
```
|-Applications (Delivered as a service)
|-Data (Delivered as a service)
|-Runtime (Delivered as a service)
|-Middleware (Delivered as a service)
|-Operating System (Delivered as a service)
|-Virtualization (Delivered as a service)
|-Servers (Delivered as a service)
|-Storage (Delivered as a service)
|-Networking (Delivered as a service)
```
## High availability 

* computing environments configured to provide nearly full time availability = high availability systems 

* built in redundant hardware / software , to avoid having single points of failure 

* When failures occur, the failover process moves processing performed by the failed component to the backup components.

## Disaster Recovery 

* Disaster recovery involves set of policites, tools and 
procedures to enable the recovery or continuation of vital technology
infrastructure and systems

* Disaster recovery key metrics :

<img src="img/1.jpg">

  > Recovery Point Objective, RPO
  * How much data loss or transaction loss can your business tolerate
  * i.e 24 hours


  > Recovery Time Objective, RTO 
  * How much downtime your business can tolerate 
  * i.e 24 hours
  * If downtime 24 hours recovery time took 48 hours , not ok


## Cloud Terminology 

* Fault Tolerance
  * Describe how a cloud vendor will ensure minimal downtime for services
    provided

   i.e If Load Balancer fail , there's a standby copy of load balancer

* Scability refers to scaling out (or in ) or scaling up (or down)
  * Horizontal scaling : scaling out(or in) 
  * Vertical scaling : scaling up(or down)

* Elasticity
  * ability to quickly increase or decrease resources 
  * storage ,database 




