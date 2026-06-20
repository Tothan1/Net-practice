*This project has been created as part of the 42 curriculum by tle-rhun.*

# NetPractice - Discover the Basics of Computer Networking

## Description
**NetPractice** is a practical educational project designed to introduce the foundational concepts of computer networking. Through a series of interactive exercises, the project focuses on configuring and troubleshooting small-scale network architectures.

The primary goal is to solve various networking problems to ensure proper device communicationrequires developing a solid understanding of how TCP/IP addressing functions, mastering subnet calculations, identifying invalid IP configurations, and implementing appropriate routing paths through gateways.

---


## Instructions

### Prerequisites
To run the training interface locally, you need a standard terminal environment with Python 3 installed to handle the local web server requirements.

### Interface Execution
The project provides a web-based simulator interface to solve the network exercises. Follow these steps to launch it:

1. Download and extract the project files into your desired workspace folder.
2. Execute the initialization script from your terminal:
```
	bash
	bash run.sh
```
or
```
	python3 -m http.server 49242
	# Open http://localhost:49242 in your web browser
```
### Dynamic Workflow & How to Export Configurations

*    Each level presents a non-functioning network diagram with specific goals shown at the top.  

*    Modify the unshaded, editable parameter fields (IPs, masks, routes) to correct the network behavior.  

*    Use the [Check again] button to validate your parameters and consult the bottom logs for error debugging.  

*    How to Export: Once a level is successfully cleared, click the [Get my config] button to export your solved configuration file before proceeding to the next level.


### Submission Requirements

*    Submission Details: You must successfully complete all 10 levels available in the training module.  

*    File Location: Exactly 10 exported configuration files (one unique file per validated level) must be placed directly at the root of your Git repository.



## Resources
### Studied Networking Concepts

In accordance with the project requirements, the following explicit networking concepts were studied and applied to complete the exercises:   

*    TCP/IP Addressing: Understanding how data packets are formatted, addressed, and routed across network networks.  

*    Subnet Masks: Calculating network and host portions, defining subnets, and managing valid address ranges.  

*    Default Gateways: Defining how devices forward traffic outside their immediate local networks using default paths.  

*    Routers and Switches: Analyzing the difference between Layer 3 IP routing infrastructure and Layer 2 bridging/switching.  

*    OSI Layers: Understanding data encapsulation and the hierarchy of network communications.

### Documentation & Cheat Sheets

*    [IT-Connect IPv4 Subnet Cheat Sheet](![IT-Connect IPv4 Subnet Cheat Sheet](https://www.it-connect.fr/wp-content-itc/uploads/2021/05/reseau-adresse-ipv4-calcul-masque-sous-reseau-12.png))- Used for its practical subnetting and IP range tables.

*    [SubnetIPv4](https://subnetipv4.com/) - Online tool utilized for validating subnet ranges and mask boundaries.

### Peer Collaboration 

In alignment with the 42 curriculum framework guidelines, both peer learning and Artificial Intelligence tools were utilized to support learning productivity:  

*    Peer Learning: Significant guidance, logic verification, and conceptual reviews were shared with classmates Rinda (ssivilay) and Mickael (mickzhan) to avoid gaps in technical understanding and validate network configurations.

### AI Usage Disclosure

*    Artificial intelligence sometimes helped me find the solution when I was struggling with a net practice exercise, but other than that, I didn't use it.