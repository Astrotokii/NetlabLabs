This is a more complex VLAN routing lab. [ h1, h2 ] are connected via VLAN 2 through SVIs on s1, which is then routed out s1's routed interface connected to e1. All switches are using RIP routing protocol. [ h3, h4 ] are connected via VLAn 3 through SVIs on s2, which is then routed out s2's routed interface connected to e2.

[ e1, e2 ] are both using RIP and are connected to each other via a Layer 3 Etherchannel. MAC addresses for port-channel 10 on each switch were manually configured with static arp. 

All hosts can ping all other hosts, confirming functional interVLAN routing. 
