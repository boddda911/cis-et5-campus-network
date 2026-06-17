<h1>Integrated Campus Network Design & Implementation</h1>

<img src="assets/preview.png" width="1000">
A comprehensive, enterprise-level network simulation designed and implemented via Cisco Packet Tracer. This project replicates a real-world, high-availability infrastructure connecting three key educational and administrative facilities within an institute's campus.

Developed as a capstone project following a rigorous 6-month Computer Networking track with IEEE ET5.

🏢 Topology Overview
The architecture establishes end-to-end connectivity across three separate buildings:

CIS (Computer Science & Systems Institute)

ET5 (Engineering Building)

Accounting (Finance & Treasury Building)

Standardized Building Layout:

Ground Floor: IT Administration Department & Core Infrastructure Servers.

1st Floor: 2 Computer Labs.

2nd Floor: Faculty Offices & 1 Computer Lab.

3rd Floor: 2 Computer Labs.

🛠️ Core Features & Technologies Implemented
VLAN Segmentation & Inter-VLAN Routing: Segregated network traffic by department and floor to enhance performance and manage broadcast domains.

Dynamic IP Allocation: Configured central DHCP servers to ensure automated, error-free IP distribution across all endpoints.

Network Services: Deployed fully functional DNS and Web Servers to simulate localized intranet environments.

Dynamic Routing (OSPF): Configured OSPF to manage efficient routing paths and ensure fast convergence between the building subnets.

Network Redundancy & High Availability: Implemented backup links and redundant pathways to eliminate single points of failure, ensuring continuous uptime during link outages.

Advanced Traffic Control (Extended ACLs): Hardened the Accounting Department by implementing strict Access Control Lists, protecting sensitive financial data from unauthorized internal and external access.

Enterprise Backup Solution: Deployed a data backup infrastructure tailored for the Accounting department to guarantee business continuity.

End-to-End Connectivity: Verified and validated via exhaustive ping tests, simulation modes, and traffic analysis.
