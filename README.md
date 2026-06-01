# Enterprise Multi-Page IIS Web Hosting Lab

## Project Overview

The environment includes IIS web hosting, DNS-based hostname resolution, Active Directory services, Windows Firewall configuration, Hyper-V virtualization, and client access validation from a domain-joined Windows 11 virtual machine.
The objective of this lab was to simulate a real-world enterprise web hosting environment commonly managed by system administrators and IT infrastructure professionals.

---

## Lab Environment

### Physical Server

* Dell PowerEdge R720

* Windows Server 2022 Standard Evaluation

### Server Roles and Features

* Internet Information Services (IIS)

![IPCONFIG](screenshots/configuration/get-service-w3svc.png)

* DNS Server

![IPCONFIG](screenshots/configuration/dns-record.png)

* Active Directory Domain Services (AD DS)

* Windows Firewall

![IPCONFIG](screenshots/configuration/firewall-rule.png)


* Hyper-V

![IPCONFIG](screenshots/configuration/hyper-v-vm.png)

![IPCONFIG](screenshots/configuration/hyper-v-manager.png)

### Client System

* Windows 11 Virtual Machine

* Domain Joined to `ravikumar.local`

---

## Website Structure



![IPCONFIG](screenshots/configuration/structure.png)








---

## Website Pages

### Home

![IPCONFIG](screenshots/webpages/updated-homepage.png)

### About

![IPCONFIG](screenshots/webpages/aboutpage.png)

### Services

![IPCONFIG](screenshots/webpages/servicespage.png)

### Projects

![IPCONFIG](screenshots/webpages/updated-projectspage2.png)

### Contact

![IPCONFIG](screenshots/webpages/contactpage.png)

## GitHub

![IPCONFIG](screenshots/webpages/github-button-added.png)


![IPCONFIG](screenshots/webpages/github-account-opened.png)

## Access from Win11-Lab VM

![IPCONFIG](screenshots/webpages/homepage-from-vm.png)

---

## DNS Configuration

Configured an Active Directory-integrated DNS record:

| Hostname | ravikumar |
|----------|-----------|
| IP Address | 192.168.2.194 |


Website access:

| Website Access | `http://ravikumar` |
|----------------|--------------------|


---

## Key Features

* Multi-page website hosting using IIS

* Custom HTML and CSS design

* Internal DNS hostname resolution

* Active Directory-integrated environment

* Windows Firewall HTTP configuration

* Domain client access validation

* Navigation menu across all pages

* Project portfolio section

* GitHub integration

* Professional website footer

---

## Skills Demonstrated

* IIS Administration

* Windows Server 2022

* DNS Management

* Active Directory

* Web Hosting

* HTML

* CSS

* Hyper-V

* TCP/IP Networking

* Windows Firewall Configuration

---


### Client Validation

* Browser access using `http://ravikumar`

---

## Outcome

Successfully designed, hosted, and managed a professional multi-page website using IIS on Windows Server 2022. The project demonstrates practical experience with enterprise web hosting, DNS configuration, Active Directory integration, and Windows Server administration.

## Author

RAVI KUMAR
