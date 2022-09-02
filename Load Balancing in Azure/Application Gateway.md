--- Application gateway

- used to load balance web traffic to web application
- uses additional HTTP attributes for routing decisison
  - Decisions based on headers or url
  - VMs, VM scasle sets, or on prem servers

- Application layer routing
- SSL termination
  - Allows you to offload encryption and decryption to the gatewar itself rather than forcing backend servers to handle it
- autoscaling 
  - Scale up or down based on traffic load, Gateway standard V2
- Web Application Firewalll
  - centeralized protection of Web apps
  - Protects against attacks like XSS or SQL injection
- zone redundency
  - Can span multiple availability zones


--- Components

- Frontend IP address
- Linstenrs are used to listen for a protocol, a port, a hostname, or an IP address and then route request
- Request routing rules used to determin routes for the listener
- Http settings determine if traffic encrypted
- Backend pools can consist o f Nics, vm scales sets, public ip address
- Health probes monitor resources in the backend pool