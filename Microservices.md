## Virtual Machines
#### Drawbacks
- Pay for ideal machine time  
## Containers 
- Ship code and dependencies in portable containers
- OS level virtualization
- Immutable container images
#### Drawbacks
- Pay for ideal machine time 
## Serverless computing 
- Everything is managed by the cloud provider
- You can focus on the business logic
- Cost per execution time, not pay for ideal time
#### Drawbacks
- its stateless

# Monolithic vs Microservices
### Monolithic 
- Monolithic is built as a single code base, separate physical layers (presentation, domain and data storage layers)
- Monolithic SOA is more granular than multi-tier architecture, where services were split up into independent loosely coupled standalone servies which spoke to each other with contracts 
- Gives holistic view of all the services 
#### Drawbacks
- single stack 
- long build and test times
- services scale togther even though not all require heavy scaling
### Microservices 
- Microservices is more like SOA
- Event driven architecture
- Domain driven 
- Small code base deployed independently 
#### Drawbacks
- lot more network traffic
- complex distributed development
