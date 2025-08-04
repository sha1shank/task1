# task1
Network scanning and vulnerability 

1.Install Nmap from official website.
2.Find your local IP range (e.g., 192.168.1.0/24).
3.Run: nmap -sS 192.168.1.0/24 to perform TCP SYN scan.
4.Note down IP addresses and open ports found.
5.Optionally analyze packet capture with Wireshark.
6.Research common services running on those ports.
7.Identify potential security risks from open ports.
8.Save scan results as a text or HTML file.

I have scanned my network range 192.168.0.1/24 and found the 192.168.0.106 192.168.0.107 running and services. 
They provide the services and founded unwanted ports open which could be potential risks. 

Summary of Actions You Should Take
Port	        Action
23	    🔐 Disable Telnet, replace with SSH
53	    🔒 Restrict DNS access, block zone transfers from unknown sources
80	    ➡️ Redirect to HTTPS (443), use SSL/TLS
1900	  🚫 Disable UPnP, especially on WAN
902	    🔒 Restrict to trusted IPs; patch VMware
912	    ❓ Investigate usage; close if unknown or unnecessary
5357	  🔒 Allow only internally; block from public internet

The above are the some open ports and services running on which could harrm the system and may lead to attack. I have scanned analyzed the traffic with wireshark and include the output file as html format in the resources and the interview questions and answers as well. 


