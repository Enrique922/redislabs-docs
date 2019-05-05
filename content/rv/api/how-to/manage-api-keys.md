---
Title: Manage API Keys
description: 
weight: 30
alwaysopen: false
categories: ["RC Pro"]
---
API requests must be performed from IP subnets that are specified as allowed subnets to this key.
Considering that, a newly created secret key does not yet provide API access to the system.

## Add a new allowed subnet

1. Click the 'Manage IPs' button associated with the key. A pop-up window appears
1. Click the plus button indicating 'Add new whitelist subnet'
1. In the text input area type in the subnet in CIDR format, **e.g.: 10.2.5.0/24**
1. Click the right icon, indicating 'Save'

After adding the subnet you can add more subnets or click 'OK' button to finish.

## Delete an allowed subnet

1. Click the 'Manage IPs' button associated with the key. A pop-up window appears
1. Click the red trashcan icon indicating 'Delete'

No confirmation pop-up appears for deleting subnets.
After deleting the subnet you can delete more subnets or click 'OK' button to finish.