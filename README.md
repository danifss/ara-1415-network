### Arquitetura Redes Avançadas (Advanced Networks Architecture)
> Ano lectivo de 2014 / 2015 - Universidade de Aveiro


#### Problem description:
* Suppose you are responsible for managing the network of operator 1000, which is an autonomous system with ID AS1000.
* Operator XY has peering relationships with AS2000 and AS3000 based on two different routers (Lisbon and Oporto).
* Consider that the different companies have the theirs IPv4 and IPv6 addresses:

#### Requirements:
* Operator 1000 should guarantee the connectivity of all IPv4 and IPv6 networks of their clients with the other companies.
* AS1000 should not be used as a transit AS between AS2000 and AS3000.
* Company A users located in Ílhavo should preferentially access CompanyC through Lisbon and CompanyD through Porto.
* In order to reduce costs and have a better security control, the Sales Department of CompanyA required virtual private connections between the Porto, Lisbon and Ílhavo poles, with a guaranteed bandwidth of 2Mbps.
* All Videoconference and VoIP traffic between the poles of CompanyA should use this private connections.
* VoIP should be based on the SIP protocol. The demonstration of this service is mandatory. For simplicity purposes, you can consider that calls are directly established between SIP terminals.
