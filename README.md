The above network topology represents one of the primary dynamic routing protocols , OSPF. 
The network topology is configured both for 3 areas and 1 area.
When pinging from system 1 in the area 1 to system 7 in area 3 , the ping is successfull thought the pc's are in a different network.
This is due to having a backbone area (area0) and ABR (Area Border Router) that share link state advertisements to updating the routing tables with neighbor information.
