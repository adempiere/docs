
.. _functional-guide/window/window-importbusinesspartner:

=======================
Import Business Partner
=======================

Import Business Partner

Help
====
The Import Business Partner Window is an interim table which is used when importing external data into the system.  Selecting the 'Process' button will either add or modify the appropriate records.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Import Business Partner
-----------------------

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.

Fields
======

Client
------
\ **Description**\ 
 \ *Client/Tenant for this installation.*\ 
\ **Help**\ 
 \ *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*\ 

Organization
------------
\ **Description**\ 
 \ *Organizational entity within client*\ 
\ **Help**\ 
 \ *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*\ 

Import Business Partner
-----------------------

Imported
--------
\ **Description**\ 
 \ *Has this import been processed*\ 
\ **Help**\ 
 \ *The Imported check box indicates if this import has been processed.*\ 

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Import Error Message
--------------------
\ **Description**\ 
 \ *Messages generated from import process*\ 
\ **Help**\ 
 \ *The Import Error Message displays any error messages generated during the import process.*\ 

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Tax ID
------
\ **Description**\ 
 \ *Tax Identification*\ 
\ **Help**\ 
 \ *The Tax ID field identifies the legal Identification number of this Entity.*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Name 2
------
\ **Description**\ 
 \ *Additional Name*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

D-U-N-S
-------
\ **Description**\ 
 \ *Dun & Bradstreet Number*\ 
\ **Help**\ 
 \ *Used for EDI - For details see   www.dnb.com/dunsno/list.htm*\ 

NAICS/SIC
---------
\ **Description**\ 
 \ *Standard Industry Code or its successor NAIC - http://www.osha.gov/oshstats/sicser.html*\ 
\ **Help**\ 
 \ *The NAICS/SIC identifies either of these codes that may be applicable to this Business Partner.*\ 

Group Key
---------
\ **Description**\ 
 \ *Business Partner Group Key*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Customer
--------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Customer*\ 
\ **Help**\ 
 \ *The Customer checkbox indicates if this Business Partner is a customer.  If it is select additional fields will display which further define this customer.*\ 

Vendor
------
\ **Description**\ 
 \ *Indicates if this Business Partner is a Vendor*\ 
\ **Help**\ 
 \ *The Vendor checkbox indicates if this Business Partner is a Vendor.  If it is selected, additional fields will display which further identify this vendor.*\ 

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

Processed
---------
\ **Description**\ 
 \ *The document has been processed*\ 
\ **Help**\ 
 \ *The Processed checkbox indicates that a document has been processed.*\ 

Import Business Partners
------------------------
\ **Description**\ 
 \ *Import Business Partners*\ 
\ **Help**\ 
 \ *The Parameters are default values for null import record values, they do not overwrite any data.*\ 

Address 1
---------
\ **Description**\ 
 \ *Address line 1 for this location*\ 
\ **Help**\ 
 \ *The Address 1 identifies the address for an entity's location*\ 

Address 2
---------
\ **Description**\ 
 \ *Address line 2 for this location*\ 
\ **Help**\ 
 \ *The Address 2 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

Address 3
---------
\ **Description**\ 
 \ *Address Line 3 for the location*\ 
\ **Help**\ 
 \ *The Address 2 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

Address 4
---------
\ **Description**\ 
 \ *Address Line 4 for the location*\ 
\ **Help**\ 
 \ *The Address 4 provides additional address information for an entity.  It can be used for building location, apartment number or similar information.*\ 

ZIP
---
\ **Description**\ 
 \ *Postal code*\ 
\ **Help**\ 
 \ *The Postal Code or ZIP identifies the postal code for this entity's address.*\ 

Additional Zip
--------------
\ **Description**\ 
 \ *Additional ZIP or Postal code*\ 
\ **Help**\ 
 \ *The Additional ZIP or Postal Code identifies, if appropriate, any additional Postal Code information.*\ 

City
----
\ **Description**\ 
 \ *Identifies a City*\ 
\ **Help**\ 
 \ *The City identifies a unique City for this Country or Region.*\ 

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Region
------
\ **Description**\ 
 \ *Identifies a geographical Region*\ 
\ **Help**\ 
 \ *The Region identifies a unique Region for this Country.*\ 

ISO Country Code
----------------
\ **Description**\ 
 \ *Upper-case two-letter alphanumeric ISO Country code according to ISO 3166-1 - http://www.chemie.fu-berlin.de/diverse/doc/ISO_3166.html*\ 
\ **Help**\ 
 \ *For details - http://www.din.de/gremien/nas/nabd/iso3166ma/codlstp1.html or - http://www.unece.org/trade/rec/rec03en.htm*\ 

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship to) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Title
-----
\ **Description**\ 
 \ *Name this entity is referred to as*\ 
\ **Help**\ 
 \ *The Title indicates the name that an entity is referred to as.*\ 

Contact Name
------------
\ **Description**\ 
 \ *Business Partner Contact Name*\ 

BP Contact Greeting
-------------------
\ **Description**\ 
 \ *Greeting for Business Partner Contact*\ 

Greeting
--------
\ **Description**\ 
 \ *Greeting to print on correspondence*\ 
\ **Help**\ 
 \ *The Greeting identifies the greeting to print on correspondence.*\ 

Contact Description
-------------------
\ **Description**\ 
 \ *Description of Contact*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Phone
-----
\ **Description**\ 
 \ *Identifies a telephone number*\ 
\ **Help**\ 
 \ *The Phone field identifies a telephone number*\ 

2nd Phone
---------
\ **Description**\ 
 \ *Identifies an alternate telephone number.*\ 
\ **Help**\ 
 \ *The 2nd Phone field identifies an alternate telephone number.*\ 

Fax
---
\ **Description**\ 
 \ *Facsimile number*\ 
\ **Help**\ 
 \ *The Fax identifies a facsimile number for this Business Partner or  Location*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Is Project Manager
------------------
\ **Description**\ 
 \ *Is Project Manager*\ 
\ **Help**\ 
 \ *Is Project Manager indicates if the contact is assigned as project manager to a project*\ 

Is Project Member
-----------------
\ **Description**\ 
 \ *Is Project Member*\ 
\ **Help**\ 
 \ *Is Project Member indicates if the contact is assigned to a project and will receive notifications of any project changes*\ 

Project Key
-----------
\ **Description**\ 
 \ *Key of the Project*\ 

Project
-------
\ **Description**\ 
 \ *Financial Project*\ 
\ **Help**\ 
 \ *A Project allows you to track and control internal or external activities.*\ 

Project Member Type Value
-------------------------
\ **Description**\ 
 \ *Define the Search Key of Project Member Type*\ 

Project Member Type
-------------------
\ **Description**\ 
 \ *Define the Member Type for a Project*\ 

Birthday
--------
\ **Description**\ 
 \ *Birthday or Anniversary day*\ 
\ **Help**\ 
 \ *Birthday or Anniversary day*\ 

Place of Birth (Location)
-------------------------
\ **Description**\ 
 \ *Place of Birth (Location)*\ 

Birth Country Code
------------------
\ **Description**\ 
 \ *Country Code of Place of Birth*\ 

Birth Country
-------------
\ **Description**\ 
 \ *Country of Place of Birth*\ 

Region of Birth
---------------
\ **Description**\ 
 \ *Name of the Region of Birth*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Region of Birth
---------------
\ **Description**\ 
 \ *Name of the Region of Birth*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Birth City
----------
\ **Description**\ 
 \ *Identifies a City of Birth*\ 
\ **Help**\ 
 \ *The City identifies a unique City for this Country or Region.*\ 

Birth Postal Zone
-----------------
\ **Description**\ 
 \ *Postal Zone of Place of Birth*\ 

Father's Name
-------------
\ **Description**\ 
 \ *Father's Name*\ 

Gender
------

Blood Group
-----------

EMail Address
-------------
\ **Description**\ 
 \ *Electronic Mail Address*\ 
\ **Help**\ 
 \ *The Email Address is the Electronic Mail ID for this User and should be fully qualified (e.g. joe.smith@company.com). The Email Address is used to access the self service application functionality from the web.*\ 

Password
--------
\ **Description**\ 
 \ *Password of any length (case sensitive)*\ 
\ **Help**\ 
 \ *The Password for this User.  Passwords are required to identify authorized users.  For Adempiere Users, you can change the password via the Process "Reset Password".*\ 

Interest Area
-------------
\ **Description**\ 
 \ *Name of the Interest Area*\ 
\ **Help**\ 
 \ *Name of the Interest Area of the user*\ 

Interest Area
-------------
\ **Description**\ 
 \ *Interest Area or Topic*\ 
\ **Help**\ 
 \ *Interest Areas reflect interest in a topic by a contact. Interest areas can be used for marketing campaigns.*\ 
