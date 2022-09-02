--- Load balancers

-- Transport layer application

- Load balancers balances traffic 
- public load balancers
  - load balances internet traffic to VMs
  - Needs public IP address
  - Provides NAT to internal VMs
- private load balancers
  - limited to cases to within azure Virtual network or on prem 

- standard load balancer
  - 1000 instances
  - avialability zones

- use cases
  - increase availability of application across vms or zones
  - Provied outbound network activity

--- load balancer components

- Frontend IP config
  - Point of contact for Clients
  - public IP address
  - Multiple IP address
- backend pool
  - collection of VM instances configured to serve requests
- health probes
  - Determine status of VMs
  - stops sending traffic to VMs that fail the heart beat
- load balancing rules
  - Rules for forwarding
- high avaiablitity ports
- Inbound Nat Rules
  - Allows to connect to internal VMs from the outside
- Outbound nat rules
  - only supported on the standard lload balancer


