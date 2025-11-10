# small-office-network
little network designing

## network topo

      [Router0]
         |
         | 
         |
      [Switch0]
      /   |   \
     /    |    \
   PC0   PC1   PC2

## objective
Network with 3 departments: 
- Engineering (VLAN 10)
- Sales (VLAN 20)
- HR (VLAn30)

* Each department is on its own logical network (VLAN) for security and performance, assinging IP using DHCP *