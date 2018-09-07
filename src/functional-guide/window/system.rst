
.. _functional-guide/window/system:

======
System
======

System Definition

Help
====
Common System Definition - Only one Record - Do not add additional records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

System
------
\ **Description**\ 
 \ *System Definition*\ 
\ **Help**\ 
 \ *Common System Definition.*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

Fields
======

System Name
-----------
\ **Description**\ 
 \ *Name your Adempiere System installation, e.g. Joe Block, Inc.*\ 
\ **Help**\ 
 \ *The name if the system to differentiate support contracts*\ 

System Status
-------------
\ **Description**\ 
 \ *Status of the system - Support priority depends on system status*\ 
\ **Help**\ 
 \ *System status helps to prioritize support resources*\ 

Registered EMail
----------------
\ **Description**\ 
 \ *Email of the responsible for the System*\ 
\ **Help**\ 
 \ *Email of the responsible person for the system (registered in WebStore)*\ 

Password
--------
\ **Description**\ 
 \ *Password of any length (case sensitive)*\ 
\ **Help**\ 
 \ *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*\ 

Support EMail
-------------
\ **Description**\ 
 \ *EMail address to send support information and updates to*\ 
\ **Help**\ 
 \ *If not entered the registered email is used.*\ 

Custom Prefix
-------------
\ **Description**\ 
 \ *Prefix for Custom entities*\ 
\ **Help**\ 
 \ *The prefix listed are ignored as customization for database or entity migration*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Release No
----------
\ **Description**\ 
 \ *Internal Release Number*\ 

Version
-------
\ **Description**\ 
 \ *Version of the table definition*\ 
\ **Help**\ 
 \ *The Version indicates the version of this table definition.*\ 

Database Name
-------------
\ **Description**\ 
 \ *Database Name*\ 

DB Address
----------
\ **Description**\ 
 \ *JDBC URL of the database server*\ 

Internal Users
--------------
\ **Description**\ 
 \ *Number of Internal Users for Adempiere Support*\ 
\ **Help**\ 
 \ *"You can purchase professional support from Adempiere, Inc. or their partners.  See http://www.adempiere.com for details.
"*\ 

Processors
----------
\ **Description**\ 
 \ *Number of Database Processors*\ 

Replication Type
----------------
\ **Description**\ 
 \ *Type of Data Replication*\ 
\ **Help**\ 
 \ *The Type of data Replication determines the direction of the data replication.  
Reference means that the data in this system is read only -> 
Local means that the data in this system is not replicated to other systems - 
Merge means that the data in this system is synchronized with the other system <-> * *\ 

ID Range Start
--------------
\ **Description**\ 
 \ *Start of the ID Range used*\ 
\ **Help**\ 
 \ *The ID Range allows to restrict the range of the internally used IDs. The standard rages are 0-899,999 for the Application Dictionary 900,000-999,999 for Application Dictionary customizations/extensions and > 1,000,000 for client data. The standard system limit is 9,999,999,999 but can easily be extended.  The ID range is on a per table basis.
Please note that the ID range is NOT enforced.*\ 

ID Range End
------------
\ **Description**\ 
 \ *End if the ID Range used*\ 
\ **Help**\ 
 \ *The ID Range allows to restrict the range of the internally used IDs. Please note that the ID range is NOT enforced.*\ 

LDAP URL
--------
\ **Description**\ 
 \ *Connection String to LDAP server starting with ldap://*\ 
\ **Help**\ 
 \ *LDAP connection string, e.g. ldap://dc.adempiere.org*\ 

LDAP Domain
-----------
\ **Description**\ 
 \ *Directory service domain name - e.g. adempiere.org*\ 
\ **Help**\ 
 \ *If LDAP Host and Domain is specified, the user is authenticated via LDAP. The password in the User table is not used for connecting to Adempiere.*\ 

Maintain Statistics
-------------------
\ **Description**\ 
 \ *Maintain general statistics*\ 
\ **Help**\ 
 \ *Maintain and allow to transfer general statistics (number of clients, orgs, business partners, users, products, invoices) to get a better feeling for the application use.  This information is not published.*\ 

Statistics
----------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics as well as general anonymous statistics*\ 

Error Reporting
---------------
\ **Description**\ 
 \ *Automatically report Errors*\ 
\ **Help**\ 
 \ *To automate error reporting, submit errors to Adempiere. Only error (stack trace) information is submitted (no data or confidential information).  It helps us to react faster and proactively.  If you have a support contract, we will you inform about corrective measures.  This functionality is experimental at this point.*\ 

Profile
-------
\ **Description**\ 
 \ *Information to help profiling the system for solving support issues*\ 
\ **Help**\ 
 \ *Profile information do not contain sensitive information and are used to support issue detection and diagnostics*\ 

Encryption Class
----------------
\ **Description**\ 
 \ *Encryption Class used for securing data content*\ 
\ **Help**\ 
 \ *The class needs to implement the interface org.compiere.util.SecureInterface.
You enable it by setting the COMPIERE_SECURE parameter of your Client and Server start scripts to the custom class.*\ 

Fail on Missing Model Validator
-------------------------------

Last Build Info
---------------

Fail if Build Differ
--------------------

Support Expires
---------------
\ **Description**\ 
 \ *Date when the Adempiere support expires*\ 
\ **Help**\ 
 \ *Check http://www.adempiere.org for support options*\ 

Validate Support
----------------
\ **Description**\ 
 \ *Validate Support Contract*\ 
\ **Help**\ 
 \ *The process connects to the Adempiere Support Services server and validates the support contract.  To sign up for support, please go to http://www.adempiere.org*\ 
