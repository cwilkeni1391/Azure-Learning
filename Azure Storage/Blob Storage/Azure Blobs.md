azcopy is a command line tool for copying data between storage containers or accounts

blobs must be copied from source to destination and then deleted from the source

Copying blobs between storage accounts is not natively supported and the same process used to copy between containers is used

powershell CloudBlockBlob class

Blob leasing allows you to take ownership of a blob. The blob can be read to during the lease but cannot delete or add.

Lease options
- acquire
- release
- renew
- break
- change

az storage  blob lease acquire --blob-name "wixard/jpg" -container-name --acount-name --account-key -lease duration

az storage blob lease release
az storage blob lease renew

----------------------------------------------------------------------

Data archiving

premium
- solid state drive 
- llow latency
- high transaction rate
- highest cost
hot
- frequently accessed data
- high storage cost
- lowest access cost
cold
- lower storage cost
- higher access cost
- 30 days
archive
- lowest storage cost
- highest access cost
- 180 days
- Data is offline
- no snap shots
- must be rehydrated to "cold or hot"

