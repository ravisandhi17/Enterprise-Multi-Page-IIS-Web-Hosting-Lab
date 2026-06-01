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

![IPCONFIG](screenshots/dhcp/SCOPE_FOR_DHCP.png)

* DNS Server

* Active Directory Domain Services (AD DS)

* Windows Firewall

* Hyper-V

### Client System

* Windows 11 Virtual Machine

* Domain Joined to `ravikumar.local`

---

## Website Structure

```
C:\inetpub\wwwroot
│
├── index.html
├── about.html
├── services.html
├── projects.html
├── contact.html
│
└── css
    └── style.css
```

---

## Website Pages

### Home

Provides an overview of the enterprise lab environment and hosted services.

### About

Contains project information and infrastructure details.

### Services

Lists technical services demonstrated within the lab environment.

### Projects

Showcases Windows Server, Active Directory, Hyper-V, and IIS projects.

### Contact

Displays administrator and server information.

---

## DNS Configuration

Configured an Active Directory-integrated DNS record:

```text
Hostname: ravikumar
IP Address: 192.168.2.194
```

Website access:

```text
http://ravikumar
```

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

## Validation

The website was successfully accessed from a domain-joined Windows 11 virtual machine using:

http://ravikumar

DNS hostname resolution, IIS web hosting, page navigation, and client connectivity were successfully tested and verified.
---

## Screenshots

### Infrastructure

* Dell PowerEdge R720 Server

* Windows Server 2022

* Hyper-V Environment

### IIS Configuration

* IIS Manager

* Default Website

* Website Files

### DNS

* DNS A Record (ravikumar)

### Website Pages

* Home Page

* About Page

* Services Page

* Projects Page

* Contact Page

### Client Validation

* Browser access using http://ravikumar

---

## Outcome

Successfully designed, hosted, and managed a professional multi-page website using IIS on Windows Server 2022. The project demonstrates practical experience with enterprise web hosting, DNS configuration, Active Directory integration, and Windows Server administration.
