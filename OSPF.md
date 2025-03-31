# OSPF
writing everything i can remember at the moment about Open Shortest Path First (OSPF) dynamic routing protocol.

# Entry
OSPF or Open Shortest Path First is an exterior , link-state dynamic routing protocol and its the most used routing protocol on the world.
OSPF administrative distance = 110
Routing Table Code = O
Multicast address = 224.0.0.5 

# OSPF Messages 
LSA - Link state advertisments , are network entries on the ospf-enabled router
(LSDB - the full ospf database made by LSAs)

Hello - message to start neighborships between routers 
DBD - Database description , is a short version of LSDB , for other routers to compare between LSDBs for a correct link-state database
LSR - Link state request , routers use this to request for more information about spf tree
LSU - Link state update , its a response to LSR or to inform about a new entry 
LSAck - Link state acknowledgement , its acknowledgement for the LSU

# OSPF Ruter roles
Backbone - is a router that is inside the backbone area (is also considered as a Internal Router) 
Internal - router inside another area 
Area Border - router that connects an area with backbone area

# OSPF Network Types
Broadcast - Ethernet & FDDI
Poit-to-point - 


to be continued
