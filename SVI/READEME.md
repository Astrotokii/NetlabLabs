This is a basic VLAN routing lab. Using SVIs on a Layer 3 Cisco switch, interVLAN routing was achieved. IPv4 pooling for this was configured in topology.yml to ensure hosts had a consistent host IP as to avoid unecessary linux IP configuration to work with the VLAN routing.

Switchport mode access needs to be configured in lab on all host links. Default gateways for all hosts need to be assigned to their corresponding VLAN ip addresses. Default gateway may need to be deleted before assigning the new VLAN ip gateway address. 
