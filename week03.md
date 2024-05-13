
Task 1. Complete the Knowledge Test

[GitHub Screenshot Demo](./images/week3task1.png)


Task 2. View ARP Table 


Screenshot of the ARP table, e.g. screenshot-arp-table.png. • List the MAC addresses of at least two other devices you discovered are “Reachable” by viewing the ARP table. Explain which computer these MAC addresses belong to and why. (E.g. is it another computer in the lab? Why do you think that?
Get-NetAdapter
get-NetNeighbor
get-NetNeighbor -ifIndex
get-NetNeighbor -ifIndex 5 -state 'reachable'
the "LinkLayerAddress" in the ARP (Address Resolution Protocol) table typically represents the MAC (Media Access Control) address of the devices in the network.
B0-7B-25-25-B5-12

B0-7B-25-22-2C-25

B0-7B-25-1F-A8-1C

74-8E-E2-38-84-EB

70-6E-6D-B9-C3-D5

The MAC addresses mentioned belong to other computers. I obtained this information using the 'get-NetAdapter' command, which displays the IP and MAC addresses of other computers.



[GitHub Screenshot Demo](./images/week3task2.png)

Task 3. Draw Network Diagrams

![GitHub Screenshot Demo](./images/week3task3.drawio)

[GitHub Screenshot Demo](./images/week3task3-1.png)


Task 4. Analyse Ping Packet Capture 

ARP (Address Resolution Protocol) packets facilitate the mapping of IP addresses to MAC addresses within a local network. Devices send ARP requests to ascertain the MAC address corresponding to a specific IP address. In return, devices owning the queried IP address respond with ARP replies, furnishing their MAC address information.

ICMP (Internet Control Message Protocol) packets serve as a common tool for network troubleshooting and diagnostics. By examining the ICMP packets, their types can be identified for analysis and understanding.

[GitHub Screenshot Demo](./images/week3task4.png)



[GitHub Screenshot Demo](./images/week3task5.png)

[GitHub Screenshot Demo](./images/week3task5-1.png)

Task 5. Learning Reflection


get-NetApadter
ping to specific domain name
get-NetNeighbor
speedtest.net
Get-ComputerInfo -Property memory
Get-ComputerInfo -Property processor
test-connection


Speedtest.net is a valuable tool for assessing internet speed, particularly when experiencing slow connections hindering online activities like video streaming. By conducting a speed test, users can compare the actual speed with the speed promised by their Internet Service Provider (ISP). If the test reveals a lower speed than what the ISP guarantees, users can use this data to communicate effectively with their provider, seeking solutions to improve their internet connection quality.
