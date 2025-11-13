# Nmap
Nmap IP Analysis Install Nmap from the official site on your laptop/PC (Windows, Linux, or Mac).

(Optional) Install Wireshark if you want to analyze network packet captures. Identify Your Local Network Range

Find your local IP address and subnet (e.g., 192.168.1.0/24).

On Windows: Run ipconfig in CMD.

On Linux/Mac: Run ifconfig in terminal. Basic TCP SYN scan command:

bash nmap -sS 192.168.1.0/24 This will scan all devices in your network and list open ports.

: Document Findings

Note down all IP addresses discovered and their open ports.

Save the scan results as a text file (output.txt) or HTML file using Nmap’s output options:

bash nmap -sS 192.168.1.0/24 -oN output.txt nmap -sS 192.168.1.0/24 -oX output.html Step 5: Optional Wireshark Packet Analysis

Capture packets while you run Nmap, then analyze using Wireshark:

Look for SYN packets, TCP handshakes, etc.

Understand how Nmap communicates with devices.

Research and Analyze Services

Research common services running on discovered open ports (e.g., HTTP, SSH, FTP, Telnet).

Use Google or search engines to understand what each port/service does.

Step 7: Identify Security Risks

For each open port/service, find out:

What security risks or vulnerabilities might be exposed?

Could these ports be entry points for attackers?

Outcome:-

I learned how to use Nmap for discovering devices and open ports in my local network.

I gained basic network reconnaissance skills, understanding how open ports can expose various network services.

I was able to identify which services are running, research their risks, and see why port management is important for network security.

I learned to document my findings and analyze potential attack vectors.

I also practiced using cybersecurity tools (Nmap, optionally Wireshark) and organizing my results for reporting and submission

What is an open port?

An open port listens for incoming connections and allows access to its service.

How does Nmap perform a TCP SYN scan?

Nmap sends SYN packets; receiving SYN-ACK means the port is open, RST means it’s closed.

What risks are associated with open ports?

Open ports can expose vulnerable services, making them entry points for attacks.

Explain the difference between TCP and UDP scanning.

TCP scanning uses connection handshakes; UDP is connectionless and relies on probe responses.

How can open ports be secured?

Close unused ports and restrict access using firewalls and strong authentication.

What is a firewall’s role regarding ports?

Firewalls allow or block network connections to ports, protecting devices from threats.

Why do attackers perform port scans?

Attackers scan ports to find open services they can exploit.

How does Wireshark complement port scanning?

Wireshark visualizes and analyzes network packets during scans to understand connections.
