--- Virtual network peering
- Vnet peering
- only peer if none overlapping IP address spaces
cant add or remove IP address ranges
- not transitive connections
- 

--- Virtual network gateways
- older than network peering
- Needs its own vnet subnet

---AZ DNS

- VMs automatically sets up name resolution
- does not work across vnets
- Pricate and public domains

- Create a zone
- record set can contain multiple records for the same name

--Private domains
- 