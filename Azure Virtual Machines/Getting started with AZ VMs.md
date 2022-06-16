What is a virtual machine?
- is an on demand scalable compute resource
- used to host application when costumer wants more control over the environment
- dont need physical hardware
- often used to extend on prem data centers
- considerations
  - vm naming conventions
  - where they are deployed
  - vm sizing requirements 
  - number of VMs
  - OS requirements

-------------------
Related resources

- Resource group must exist
- virtual network and virtual nic is required
- a storage accounts for unmanaged disks
- a public IP is required for public access
- data disks can added to a VM

---------------------------
AZure VM Pricing
- Pay as you go
  - pay by the second
  - no llong term commitment
  - no upfront payment
  - pay only what you use
  - low cost and flexible option
- reserved VM instances
  - an advanced purchase for 1 to 3 years
  - upfront purchase up to 72% cheaper
  - best option if you have applications with steady state usage
  - offers budget predictability
- Spot pricing
  - purchase unsude compute capacity
  - upto 90% cheaper
  - workloads run on spot instances must tolerate interruptions
  - a good option if you are running interruptible appllications
  - Very low compute cost


- -----------------------------------
virtual machine options
- General purpose
  - balanced cpu to memory 

- Compute optimized
  - high cpu to memory 
  - good for batch processing

- memory optimized 
  - high memory to core ration
  - database

- storage optimized
  - high disk IO

- GPU 
- - graphic rendering and video editing

- high performance compute
  - designed to handle I performance compute workloads
  - high through put network interfaces

------------------------------------------