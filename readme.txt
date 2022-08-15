This repository and all it's content belongs to ANAS MURTAZA.

A C++ model is developed which simulates all the network layers of the network protocol stacks.
PHYSICAL LAYER -> DATA LINK LAYER -> NETWORK LAYER -> TRANSPORT LAYER -> APPLICATION LAYER

PHYSICAL LAYER-> creation of end devices, communication between them and hub network was implemented.
DATA LINK LAYER-> BRIDGES, SWITCH and various access control, flow control(GO_BACK_N, STOP AND WAIT) and error control(CRC and &-bit HAMMING CODE) protocols were implemented in it.

NETWORK LAYER-> ROUTERS were implemented in it. Various protocols like OSPF AND RIP were included. Apart from these, routing tables and general case topology of network were also included with the use of graph and shortest path algorithm. LONGEST MASK MATCHING also is a part of it.

TRANSPORT LAYER-> Assigning various ephemeral ports and well known ports to various process. UDP datframe used. Flow control protocols of data link layer were also included in it.

APPLICATION LAYER-> various protocols like HTTP, SSH, FTP, DNS were implemented in it.

ADD ONS: IPV6 implementation and clasful addressing were included.


SPECIAL IMPROVEMENT IN PROJECT -------->  NOW TWO DEVICES HAVING THESE FILES CAN COMMUNICATE WITH EACH OTHER AND DATA FRAME UDP CAN SIMULATE BETWEEN THEM.
(REQUIREMENT- 
both device must have windows 10 pro for it.
for transfer simulation between two device:
both device must enable message services.
go to ADMISTRATIVE SERVICES AND ENABLE MESSAGING SERVICES.
OPEN CMD- TYPE control admintools
then double click component service
then select services (local)
turn on message services.)

Incase of any doubt/suggestion/technical_problem, feel free to contact on anasmurtaza33@gmail.com
