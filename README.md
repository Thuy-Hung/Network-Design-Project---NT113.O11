# Network Design for O-UIT Outsourcing Company
## Documentation
[Documentation](https://drive.google.com/file/d/1K0o1txtt1g1A3zu_i8aN49EX1GBwumhd/view?usp=drive_link)
## Overview
This project is conducted by Group 10, Class NT113.O11, Faculty of Computer Networks and Communications, University of Information Technology - VNU-HCM. We designed a network system for Outsource O-UIT with a headquarters in Thu Duc and a branch in District 3.


### 1. Headquarters
The headquarters is a five-story building that includes a Data Center and various offices for CEO, HR, Project Managers, Technical Managers, Business Analysts, IT Managers, and teams of Developers and Testers working on international projects. The building layout is as follows:

- **1st Floor**: Reception area, guest room, HR office, and a break area.
- **2nd Floor**: Workspace for Developers and Testers.
- **3rd Floor**: Technical Manager and IT Manager offices, and a small meeting room.
- **4th Floor**: Data Center and storage.
- **5th Floor**: CEO's office, project room (BA), and a large meeting room.

### 2. Branch Office (District 3)
The branch office accommodates Developer and Tester teams working on domestic projects.

## Requirements
O-UIT Outsourcing Company has specific networking requirements for both locations:

### **Headquarters**
- Developers and Testers must use company-provided desktop computers; personal laptops are not allowed to access the company network.
- CEO, HR, Project Managers, Technical Managers, Business Analysts, and IT Operations staff are allowed to use laptops and connect to the internal WiFi system with authentication.
- A public WiFi system with a separate internet connection must be available.
- Hardware infrastructure must support virtualization for deploying applications in the testing phase.
- Cloud services must be used to deploy applications in the staging phase for customer testing before going live.

### **Branch Office**
- Developers and Testers must use company-provided desktop computers and are not allowed to use personal laptops on the network.
- A **VPN site-to-site connection** must be implemented to access internal servers and deploy applications to the Data Center.
- A WiFi system with a separate internet connection must be available.

## Subject Information
- **Course**: Network Design
- **Department**: Computer Networks and Communications
- **Project Type**: Major Assignment Report

