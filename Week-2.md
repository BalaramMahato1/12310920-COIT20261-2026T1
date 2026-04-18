Week2 Portfolio

Task 1: Setting Static IP Addresses

Aim
Three different approaches to setting a static IP address on a Linux host.

Activities Completed
 1. Created a new GNS3 project named Setting-IP-12310920.
     ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Created-Project.png)
 2. Add four nodes of type Linux Host and one Ethernet switch, and connect together into a LAN.
     ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Connected-Nodes.png)                                                                                       
 4. Selected an IPv4 network address (192.168.10.0/24) to use in LAN.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Configure-Network.png)
    
 5. For two of the hosts, I use the GNS3 Configure menu item to set static IP addresses on the nodes.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Config-HostA.png)
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Config-HostB.png)
    
 7. Start all nodes.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Started-All-Node.png)
    
 11. On the 3rd and 4th hosts, opened a console and used the ip address add command to set a static IP address.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Config-HostC.png)
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Config-HostD.png)

 13. Used the IP address show command to view and check the IP addresses of all four hosts.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Addresses-HostA.png)
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Addresses-HostB.png)
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Addresses-HostC.png)
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-IP-Addresses-HostD.png)

Task 2: Testing Network Connectivity and Delay with Ping
1.  Ping from host A to host B and stop the ping after at least five (5) response messages are received.
    ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Simple.png)
    
2.	Ping from the host A to an IP address that does not exist in my network and  wait at least 10 seconds before stopping the ping.
   ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Error.png)
  	
3. Ping from the host C to host B by changing the count.
   ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Count.png)
   
4. Ping from the host C to host B by changing the interval.
   ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Interval.png)

5. Ping from the host C to host B by changing the size.
   ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Size.png)

6. Ping from the host C to host B by combined options.
   ![GNS3 Screenshot](./File/Week2/Screenshots/Week2-Ping-Basic-12310920-Combined.png)
