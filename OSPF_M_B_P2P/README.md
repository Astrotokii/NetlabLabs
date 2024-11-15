This is a scaled down version of 3 "offices" and 1 "server/datacenter" topology using OSPF, VLANs, SVIs, P2P OSPF network redundancy for the Ethernet WANs connecting the locations, and LANs for each office with redundant routers (OSPF BDRs).

I noticed that my OSPF multiarea topology (see Multiarea_OSPF) lacked LANs and overall the topology was rather sloppy and naming was somewhat confusing. This topology is more tidy and more functional. All hosts can ping across VLANs and Subnets, all OSPF areas are sectioned as intended and packet travel is routed as engineered.
