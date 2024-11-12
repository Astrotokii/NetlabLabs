This is a VLAN routing lab, using SVIs on host links and routed interface links between l3 (l3 switch) and r1 (router). 

For the lab to work, switchport mode access needs to be enabled on host links on l3. VLAN 10 and 20 on l3 need ip address assigning. 

For all hosts, the default gateway needs to be deleted and changed to their corresponding VLAN ip addresses on l3. 

Once this is done, VLAN 10 hosts are able to ping VLAN 20 hosts, confirming VLAN routing via SVI/RoutedIF. 
