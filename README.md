# DNAT-SNAT

Question 2 _Networks: For Both Backend and Full Stack
            
2.1 Explain the concepts of Default Gateway in IP
A default gateway makes it possible for devices in one network to communicate with devices in another network. If a computer, for example, requests a web page, the request goes through the default gateway before exiting the local network to reach the internet. 
Default gateway act as an intermediate device between the local network and the internet. The default gateway transfers internal data to the internet and back again.
	
2.2 Explain the concepts of SNAT and DNAT

SNAT
•	SNAT stands for Source Network translation.
•	In SNAT source IP address is modified. SNAT basically changes the source address in the IP header.
•	On the other side of NAT device, we have outside world and inside world.
•	SNAT happens when inside world communicate with the outside world.
•	SNAT allows multiple hosts on the "Inside" to get any host on the "Outside"
•	When many internal private IP addresses gets translated to one public IP address it’s called statics SNAT.
•	Static SNAT is one to one mapping of a private IP addresses to a public IP address.
•	It is useful when a network device needs to be accessible from the internet.
•	Source address: 10.0.0.X
•	Destination address: 196.97.98.99

 

DNAT
•	DNAT stands for Destination NAT.
•	It happens when outside word communicates with the inside world.
•	DNAT allows multiple hosts on the outside to get to any host on the inside.
•	When many internal private IP addresses get translated to many public IP addresses it’s called Dynamic SNAT.
•	Dynamic SNAT can be defined as mapping of private IP address to a public IP address from a group of public IP address called NAT pool.
•	Dynamic NAT establishes a one to one mapping between the two.
•	Source address: 96.97.98.99
•	Destination address: 12.34.36.78
 
