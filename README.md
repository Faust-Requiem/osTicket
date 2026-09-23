# osTicket
Implementation

# osTicket Help Desk Implementation on Ubuntu Server

## Project Summary

This project documents the implementation of an osTicket help desk
environment running on an Ubuntu Server virtual machine. The project
covers the installation and configuration of the required server
components, deployment of osTicket, database configuration, and
verification of the help desk ticketing system.

### Project Type

Technology implementation and hands-on IT support lab.

### Environment

- Oracle VirtualBox
- Ubuntu Server

### Applications and Services

- Apache HTTP Server
- PHP
- MariaDB
- osTicket

### Languages / Technologies

- Bash
- SQL
- PHP
- Linux command line

---

# Project Objectives

The objectives of this project were to:

- Deploy an Ubuntu Server virtual machine.
- Configure Apache as the web server.
- Install and configure PHP and required extensions.
- Install and configure MariaDB.
- Create an osTicket database and database user.
- Deploy osTicket to the Apache web root.
- Configure osTicket through its web installer.
- Verify the staff control panel.
- Create and manage a test support ticket.
- Troubleshoot installation and configuration issues.

---

# Prerequisites

Before installing osTicket, the following components were prepared:

- Oracle VirtualBox
- Ubuntu Server
- Apache
- PHP
- Required PHP extensions
- MariaDB
- Network connectivity
- osTicket installation package

---

# Demonstration

## 1. Virtual Machine Environment

The project was performed inside an Ubuntu Server virtual machine
running through Oracle VirtualBox.

![VirtualBox Configuration](<img width="1210" height="528" alt="Screenshot 2026-09-23 132246" src="https://github.com/user-attachments/assets/1a97c266-c84c-4090-b080-77600b177eb9" />
)

---

## 2. Ubuntu Server

The Ubuntu Server environment was installed and configured as the
foundation for the help desk application.

![Ubuntu Server](screenshots/02-ubuntu.png)

---

## 3. Apache Web Server

Apache was installed and verified as an active service.

![Apache Status](screenshots/03-apache.png)

---

## 4. PHP Configuration

PHP and the required extensions were installed and verified.

![PHP Configuration](screenshots/04-php.png)

---

## 5. MariaDB Database

MariaDB was installed and configured to provide the database backend
for osTicket.

![MariaDB](screenshots/05-mariadb.png)

---

## 6. osTicket Deployment

The osTicket application files were extracted and deployed to the
Apache web root.

![osTicket Files](screenshots/06-osticket-files.png)

---

## 7. osTicket Requirements

The osTicket web installer was used to verify that the server met the
application requirements.

![osTicket Requirements](screenshots/07-requirements.png)

---

## 8. Installation

The osTicket web installer was completed using the configured database
and administrator account.

![Installation](screenshots/08-installation.png)

---

## 9. Staff Control Panel

After installation, I logged into the osTicket Staff Control Panel
to verify that the application was functioning correctly.

![Staff Panel](screenshots/09-staff-panel.png)

---

## 10. Creating a Support Ticket

A test support ticket was created to demonstrate the ticketing
workflow.

![Test Ticket](screenshots/10-ticket.png)

---

## 11. Ticket Management

The ticket was reviewed and managed through the osTicket staff
interface.

![Ticket Resolution](screenshots/11-ticket-resolution.png)

---

# Troubleshooting

During implementation, several issues were encountered and
troubleshot, including web server/application errors and PHP
dependency issues.

Each issue was approached by:

1. Identifying the symptom.
2. Checking the relevant service or configuration.
3. Determining the underlying cause.
4. Applying a corrective action.
5. Verifying that the issue was resolved.

---

# Skills Demonstrated

- Linux system administration
- Virtual machine configuration
- Apache web server administration
- PHP configuration
- MariaDB database administration
- SQL
- Application deployment
- Service troubleshooting
- Command-line troubleshooting
- Help desk/ticketing system administration
- Technical documentation
