Availability sets and Availability zones
- Availabilty set
  -   redundancy and availability for VMs
  -   Deploying at least two virtual machines into an availablity set ensure that at least one of them remains available whenever planned or unplanned maintenance occurs
  -   every VM that is deployed into an availability set is assigned an update domain and a fault domain by Azure
  -   an update domain is a group of VM and physical hardware that can be rebooted at the same time
  -   when planned maintenance is performed on the Azure platform, only one update domain is rebooted at a time.
  -   Ensures VMS and associated hardware are not taken down at the same time

- Fault domain
  - is a group of VMs that shares a common power source and a common network switch
  - VMs in an availablity set are distributed across up to three different fault domains in resource manager or across two fault domains in classic deployments


- Availability Zones
  - Protect applications from complete azure data center failures
  - multiple availability zones in an azure region
  - Deployed into different update domains