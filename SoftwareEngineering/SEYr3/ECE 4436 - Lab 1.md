## Task 1
###### Question 1
What is your device IP address, are there any rows where you do not see it

IPv6: 2607:fea8:29e2:6400:358b:5795:84fd:6dbf
IPv4: 10.0.0.71

yes there are a number of other rows with differing IP addresses. SSDP, MDNS, and ICMPv6 protocols always had different IP addresses 
###### Question 2
How many packets in total were captured?

182
###### Question 3
TCP made up 54% of packets and UDP made up 14% of packets

## Task 2
###### Question 1
128.119.245.12
###### Question 2
Print the two HTTP messages (GET and OK) referred to in question 2 above
![[Pasted image 20230925210645.png]]
![[Pasted image 20230925210713.png]]
###### Question 3
How much time did it take to deliver the website to your device?

0.0512 s
###### Question 4
How much longer did it take the second time when you made the same request for the page?

it took .0051 s shorter for the second request
###### Question 5
What do you attribute the change in time between the two to?

I believe that the webpage refreshed faster because it retrieved as much information as it could from the cache rather than having to ping the server
## Task 3
###### Question 1
Choose a local business in London and trace-route your connection to their website

How many hops were taken and at which hop did you reach the ISP, what is the ISP of the server, what is the IP address of the website URL you chose

\www.largnet.ca

12 hops were taken. The ISP was reached on the 5th hop. The ISP of the server was PROLEXIC-TECHNOLOGIES-DDOS-MITIGATION-NETWORK, US and the IP address is 198.185.159.144

![[Pasted image 20230925224156.png]]
###### Question 2
Choose any business that is not hosted in north america or south america and trace-route your connection to their website.

How many hops were taken, at which hop did your connection exit Canada, what is the IP address of the website URL you chose

rwb.jp. 18 hops were taken. The connection exited canada on the 5th hop. the IP address is 157.7.107.47

![[Pasted image 20230925224209.png]]
## Task 4
###### Question 1
What is your public IP, Attempt to ping this IP from the trace-route website. how many packets were lost? What is the location of the second last hop?

my public ip is 99.243.242.158. 0 packets were lost and the second last hop is Canada
###### Question 2
How many ISPs did you go through?

2 different ISPs

![[Pasted image 20230925224219.png]]



