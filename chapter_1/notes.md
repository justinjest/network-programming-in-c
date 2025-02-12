## Chapter 1 notes

OSI layer model vs tcp/ip layer model

When programming you only need to consider the highest level of abstraction you are using. If you are making a website you only need to worry about http/html/css, not how the tcp/ip interactions occur.

Domain names use DNS to connect a website name into anip address

To determine if you should use IPv6 or IPv4 we send a request to the server requesting a AAAA-type record for 6, if we don't get one we request an a type record, which would be 4

Unicast is when packets are routed from one sender to one receiver
Broacast allows a single sender to address a packet to all recipients
Anycast deliver a message to one recipient, but  you don't care which one responds. This can be used as a kind of load balancing system. 

A socket is one end-point of a communication link between systems.  It consists of 5 things
- local IP
- Local Port
- Remote IP address
- Remote port
- Protocol

## Questions for research
Is HTTPS get requests unicast? 
