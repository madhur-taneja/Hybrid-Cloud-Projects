# Hybrid Cloud SaaS: Three-tier web application
**Course 3: Public and Hybrid Cloud Management**

Our fictitious example company is **The E-Commerce Company,** with a stock symbol of **TECC**, hence you will see naming standards which use: tecc.

## Table of Contents

- [Getting Started](#getting-started)
- [Credentials](#credentials)
	- [SSH KEYS](#ssh-keys)
	- [PRISM CENTRAL](#prism-central)
	- [PRISM BEAM](#prism-beam)
- [Blueprint](#blueprint)

## Getting Started

The TECC Software Release manager has coordinated with the Database Administrator team to define a test application and test database schema:

- tecc_webuser@webapp.[tecc_dba_test.sql](tecc_dba_test.sql)
- [tecc_dba_test.php](tecc_dba_test.php)

The test application and database are used to verify a new workload deployment has a baseline of connectivity and functionality to insure developer productivity "out of the box," including ad-hoc database operations:

- [database backup](MySQL_backup_file.sh.txt)
- [database restore](MySQL_restore.sh.txt)

## Credentials

### SSH KEYS

* id_rsa - WebServer
* id_rsa_1 - Database

### PRISM CENTRAL

* Password: nutanix/4u

### PRISM BEAM:

* ID: hce-beam16@udacity.com
* Password: Nutanix1234@

## Blueprint

[Hybrid-Cloud-Saas-Three-Tier-Application](Hybrid-Cloud-Saas-Three-Tier-Application.json) contains the final submission blueprint
