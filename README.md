#This Azure Resource Manager template will deploy:
1 network interface card
1 network security group
1 public IP address
1 Virtual Machine Standard_B1 approx $20AUD/month
1 Standard_LRS (local redundancy storage) disk
1 virtual network

## Network Rules
Network rules are applied at the Network Security group
Allows all inbound traffic on SSH, RDP, HTTP, HTTPS
Ports 22, 80, 3389, 443

**NOT SUITABLE FOR PRODUCTION

See additional references here: https://learn.microsoft.com/en-us/azure/templates/microsoft.compute/virtualmachines?pivots=deployment-language-arm-template