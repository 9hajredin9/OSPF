# OSPF
writing everything i can remember at the moment about Open Shortest Path First (OSPF) dynamic routing protocol.

# Entry
OSPF or Open Shortest Path First is an exterior , link-state dynamic routing protocol and its the most used routing protocol on the world. <br>
OSPF administrative distance = 110 <br>
Routing Table Code = O <br>
Multicast address = 224.0.0.5  <br>

# OSPF Messages 
LSA - Link state advertisments , are network entries on the ospf-enabled router <br>
(LSDB - the full ospf database made by LSAs) <br>

Hello - message to start neighborships between routers  <br>
DBD - Database description , is a short version of LSDB , for other routers to compare between LSDBs for a correct link-state database <br>
LSR - Link state request , routers use this to request for more information about spf tree <br>
LSU - Link state update , its a response to LSR or to inform about a new entry  <br>
LSAck - Link state acknowledgement , its acknowledgement for the LSU <br> 

# OSPF Ruter roles
Backbone - is a router that is inside the backbone area (is also considered as a Internal Router)  <br>
Internal - router inside another area  <br>
Area Border - router that connects an area with backbone area <br>
Autonomous System Boundary Router - router that is advertising a default route <br>

# OSPF Network Types
Broadcast - Ethernet & FDDI <br>
Poit-to-point - PPP & HDLC <br>
Non-Broadcast - Frame-relay & X.25 <br>


# OSPF States

Down - Router is not configured with OSPF <br>
innit - Interface gets enabled with ospf and sends hello messagess with its ID <br>
Two-Way - 2 Routers for full adjacency and elect DR and BDR <br>
exStart - Routers elect a master and slave to start exchanging DBDs <br>
Exchange - Routers start exchanging DBDs <br>
Loading - Routers Send Link-State Requests for more entries <br>
Full - Routers LSDBs are identic and the spanning tree is accurate <br>


