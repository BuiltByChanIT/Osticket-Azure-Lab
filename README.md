# osTicket Help Desk Deployment in Azure

## Overview
Deployed and configured the osTicket help desk ticketing system in Microsoft Azure on a Windows Server VM using IIS, PHP, and MySQL. Validated functionality by creating, assigning, and resolving tickets through the agent workflow.

## Architecture
- 1x Windows Server VM (osticket-01)
- IIS Web Server + PHP (FastCGI)
- MySQL database
- osTicket application hosted on IIS

## Technologies Used
- Microsoft Azure (Virtual Machines, Networking)
- Windows Server
- IIS
- PHP
- MySQL
- osTicket

## Deployment Steps (High-Level)
1. Created an Azure Resource Group and deployed a Windows Server VM
2. Installed IIS and required web server components
3. Installed PHP and configured IIS for PHP support (FastCGI)
4. Installed MySQL and created an osTicket database/user
5. Installed and configured osTicket in IIS
6. Validated full ticket lifecycle (create → assign → resolve/close)

## Validation
Screenshots in `/screenshots` demonstrate:
- IIS installation and configuration
- osTicket installation/configuration
- Ticket creation, assignment, and resolution

## Skills Demonstrated
- Ticketing system deployment and administration
- IIS web server configuration
- Basic database setup and application configuration
- Help desk workflow and documentation
