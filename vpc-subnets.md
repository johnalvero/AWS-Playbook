Many (if not all of the workloads) can be hosted in a three-tier architecture.

### DMZ
  - Load Balancers, Jump/Bastion Servers, Proxy Servers, NAT instance
  - Application instances may be hosted here if there is a strong use-case
  - Open ports 80, 443 and any other application port

### Private
  - Application instances
  - Allow traffic from DMZ and DB **ONLY**
  - Use a NAT/Proxy server to make outgoing internet traffic

### DB
  - Database hosts, RDS and others
  - Caching endpoints like Redis
  - No internet access

![Three-tier diagram](https://github.com/johnalvero/AWS-Playbook/blob/master/images/thee-tier-sample.jpeg)
