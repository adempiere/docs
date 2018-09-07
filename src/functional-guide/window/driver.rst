
.. _functional-guide/window/driver:

======
Driver
======

Maintain Driver

Help
====
The Driver window allows to define Vehicle operator

Window Type
-----------
\ **Maintain**\ 


Tabs
====

Driver
------

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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Driver Status
-------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Driver Copy
-----------

Requirement Assignment
----------------------
\ **Description**\ 
 \ *Process which will assignment Requirement to Driver*\ 

License Assignment
------------------
\ **Description**\ 
 \ *Process which will assignment License*\ 

Requirement Assignment
----------------------
\ **Description**\ 
 \ *Process which will assignment Requirement to Drive*\ 

License Types Assignment
------------------------

Business Partner
----------------
\ **Description**\ 
 \ *Business Partner*\ 

.. note::
    The Single Row Layout checkbox indicates if the default display type for this window is a single row as opposed to multi row.

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

Search Key
----------
\ **Description**\ 
 \ *Search key for the record in the format required - must be unique*\ 
\ **Help**\ 
 \ *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*\ 

Employee
--------
\ **Description**\ 
 \ *Indicates if  this Business Partner is an employee*\ 
\ **Help**\ 
 \ *The Employee checkbox indicates if this Business Partner is an Employee.  If it is selected, additional fields will display which further identify this employee.*\ 

Greeting
--------
\ **Description**\ 
 \ *Greeting to print on correspondence*\ 
\ **Help**\ 
 \ *The Greeting identifies the greeting to print on correspondence.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Summary Level
-------------
\ **Description**\ 
 \ *This is a summary entity*\ 
\ **Help**\ 
 \ *A summary entity represents a branch in a tree rather than an end-node. Summary entities are used for reporting and do not have own values.*\ 

Credit Status
-------------
\ **Description**\ 
 \ *Business Partner Credit Status*\ 
\ **Help**\ 
 \ *Credit Management is inactive if Credit Status is No Credit Check, Credit Stop or if the Credit Limit is 0.
If active, the status is set automatically set to Credit Hold, if the Total Open Balance (including Vendor activities)  is higher then the Credit Limit. It is set to Credit Watch, if above 90% of the Credit Limit and Credit OK otherwise.*\ 

Open Balance
------------
\ **Description**\ 
 \ *Total Open Balance Amount in primary Accounting Currency*\ 
\ **Help**\ 
 \ *The Total Open Balance Amount is the calculated open item amount for Customer and Vendor activity.  If the Balance is below zero, we owe the Business Partner.  The amount is used for Credit Management.
Invoices and Payment Allocations determine the Open Balance (i.e. not Orders or Payments).*\ 

Tax ID
------
\ **Description**\ 
 \ *Tax Identification*\ 
\ **Help**\ 
 \ *The Tax ID field identifies the legal Identification number of this Entity.*\ 

SO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on sales*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on sales, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

PO Tax exempt
-------------
\ **Description**\ 
 \ *Business partner is exempt from tax on purchases*\ 
\ **Help**\ 
 \ *If a business partner is exempt from tax on purchases, the exempt tax rate is used. For this, you need to set up a tax rate with a 0% rate and indicate that this is your tax exempt rate.  This is required for tax reporting, so that you can track tax exempt transactions.*\ 

Tax Group
---------

D-U-N-S
-------
\ **Description**\ 
 \ *Dun & Bradstreet Number*\ 
\ **Help**\ 
 \ *Used for EDI - For details see   www.dnb.com/dunsno/list.htm*\ 

Reference No
------------
\ **Description**\ 
 \ *Your customer or vendor number at the Business Partner's site*\ 
\ **Help**\ 
 \ *The reference number can be printed on orders and invoices to allow your business partner to faster identify your records.*\ 

NAICS/SIC
---------
\ **Description**\ 
 \ *Standard Industry Code or its successor NAIC - http://www.osha.gov/oshstats/sicser.html*\ 
\ **Help**\ 
 \ *The NAICS/SIC identifies either of these codes that may be applicable to this Business Partner.*\ 

Rating
------
\ **Description**\ 
 \ *Classification or Importance*\ 
\ **Help**\ 
 \ *The Rating is used to differentiate the importance*\ 

Business Partner Group
----------------------
\ **Description**\ 
 \ *Business Partner Group*\ 
\ **Help**\ 
 \ *The Business Partner Group provides a method of defining defaults to be used for individual Business Partners.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this Business Partner if Multi-Language enabled*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting documents. It requires, that on Client level, Multi-Lingual documents are selected and that you have created/loaded the language.*\ 

URL
---
\ **Description**\ 
 \ *Full URL address - e.g. http://www.adempiere.org*\ 
\ **Help**\ 
 \ *The URL defines an fully qualified web address like http://www.adempiere.org*\ 

Prospect
--------
\ **Description**\ 
 \ *Indicates this is a Prospect*\ 
\ **Help**\ 
 \ *The Prospect checkbox indicates an entity that is an active prospect.*\ 

Link Organization
-----------------
\ **Description**\ 
 \ *Link Business Partner to an Organization*\ 
\ **Help**\ 
 \ *If the Business Partner is another Organization, select the Organization or set to empty to create a new Organization.  You link a Business Partner to an Organization to create explicit Documents for Inter-Org transaction.
If you create a new Organization, you may supply a Organization Type.  If you select a Role, the access to the new Organization is limited to that role, otherwise all (non manual) roles of the Client will have access to the new Organization.*\ 

Potential Life Time Value
-------------------------
\ **Description**\ 
 \ *Total Revenue expected*\ 
\ **Help**\ 
 \ *The Potential Life Time Value is the anticipated revenue in primary accounting currency to be generated by the Business Partner.*\ 

Actual Life Time Value
----------------------
\ **Description**\ 
 \ *Actual Life Time Revenue*\ 
\ **Help**\ 
 \ *The Actual Life Time Value is the recorded revenue in primary accounting currency generated by the Business Partner.*\ 

Acquisition Cost
----------------
\ **Description**\ 
 \ *The cost of gaining the prospect as a customer*\ 
\ **Help**\ 
 \ *The Acquisition Cost identifies the cost associated with making this prospect a customer.*\ 

Employees
---------
\ **Description**\ 
 \ *Number of employees*\ 
\ **Help**\ 
 \ *Indicates the number of employees for this Business Partner.  This field displays only for Prospects.*\ 

Share
-----
\ **Description**\ 
 \ *Share of Customer's business as a percentage*\ 
\ **Help**\ 
 \ *The Share indicates the percentage of this Business Partner's volume of the products supplied.*\ 

Sales Volume in 1.000
---------------------
\ **Description**\ 
 \ *Total Volume of Sales in Thousands of Currency*\ 
\ **Help**\ 
 \ *The Sales Volume indicates the total volume of sales for a Business Partner.*\ 

First Sale
----------
\ **Description**\ 
 \ *Date of First Sale*\ 
\ **Help**\ 
 \ *The First Sale Date identifies the date of the first sale to this Business Partner*\ 

Logo
----

Bank Account
------------
\ **Description**\ 
 \ *Define Bank Account*\ 
\ **Help**\ 
 \ *The Define Bank Account Tab defines the banking information for this business partner.  This data is used for processing payments and remittances.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

User/Contact
------------
\ **Description**\ 
 \ *User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

ACH
---
\ **Description**\ 
 \ *Automatic Clearing House*\ 
\ **Help**\ 
 \ *The ACH checkbox indicates if this Bank Account accepts ACH transactions.*\ 

Account Usage
-------------
\ **Description**\ 
 \ *Business Partner Bank Account usage*\ 
\ **Help**\ 
 \ *Determines how the bank account is used.*\ 

Bank
----
\ **Description**\ 
 \ *Bank*\ 
\ **Help**\ 
 \ *The Bank is a unique identifier of a Bank for this Organization or for a Business Partner with whom this Organization transacts.*\ 

Bank Account Type
-----------------
\ **Description**\ 
 \ *Bank Account Type*\ 
\ **Help**\ 
 \ *The Bank Account Type field indicates the type of account (savings, checking etc) this account  is defined as.*\ 

Routing No
----------
\ **Description**\ 
 \ *Bank Routing Number*\ 
\ **Help**\ 
 \ *The Bank Routing Number (ABA Number) identifies a legal Bank.  It is used in routing checks and electronic transactions.*\ 

Account No
----------
\ **Description**\ 
 \ *Account Number*\ 
\ **Help**\ 
 \ *The Account Number indicates the Number assigned to this bank account.*\ 

Credit Card
-----------
\ **Description**\ 
 \ *Credit Card (Visa, MC, AmEx)*\ 
\ **Help**\ 
 \ *The Credit Card drop down list box is used for selecting the type of Credit Card presented for payment.*\ 

Number
------
\ **Description**\ 
 \ *Credit Card Number*\ 
\ **Help**\ 
 \ *The Credit Card number indicates the number on the credit card, without blanks or spaces.*\ 

Verification Code
-----------------
\ **Description**\ 
 \ *Credit Card Verification code on credit card*\ 
\ **Help**\ 
 \ *The Credit Card Verification indicates the verification code on the credit card (AMEX 4 digits on front; MC,Visa 3 digits back)*\ 

Exp. Month
----------
\ **Description**\ 
 \ *Expiry Month*\ 
\ **Help**\ 
 \ *The Expiry Month indicates the expiry month for this credit card.*\ 

Exp. Year
---------
\ **Description**\ 
 \ *Expiry Year*\ 
\ **Help**\ 
 \ *The Expiry Year indicates the expiry year for this credit card.*\ 

Account Name
------------
\ **Description**\ 
 \ *Name on Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Name of the Credit Card or Account holder.*\ 

Account Street
--------------
\ **Description**\ 
 \ *Street address of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Street Address of the Credit Card or Account holder.*\ 

Account City
------------
\ **Description**\ 
 \ *City or the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Account City indicates the City of the Credit Card or Account holder*\ 

Account Zip/Postal
------------------
\ **Description**\ 
 \ *Zip Code of the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Zip Code of the Credit Card or Account Holder.*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Account Country
---------------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *Account Country Name*\ 

Driver License
--------------
\ **Description**\ 
 \ *Payment Identification - Driver License*\ 
\ **Help**\ 
 \ *The Driver's License being used as identification.*\ 

Social Security No
------------------
\ **Description**\ 
 \ *Payment Identification - Social Security No*\ 
\ **Help**\ 
 \ *The Social Security number being used as identification.*\ 

Account EMail
-------------
\ **Description**\ 
 \ *Email Address*\ 
\ **Help**\ 
 \ *The EMail Address indicates the EMail address off the Credit Card or Account holder.*\ 

Address verified
----------------
\ **Description**\ 
 \ *This address has been verified*\ 
\ **Help**\ 
 \ *The Address Verified indicates if the address has been verified by the Credit Card Company.*\ 

Zip verified
------------
\ **Description**\ 
 \ *The Zip Code has been verified*\ 
\ **Help**\ 
 \ *The Zip Verified indicates if the zip code has been verified by the Credit Card Company.*\ 

Location
--------
\ **Description**\ 
 \ *Define Location*\ 
\ **Help**\ 
 \ *The Location Tab defines the physical location of a business partner.  A business partner may have multiple location records.*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Address
-------
\ **Description**\ 
 \ *Location or Address*\ 
\ **Help**\ 
 \ *The Location / Address field defines the location of an entity.*\ 

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

ISDN
----
\ **Description**\ 
 \ *ISDN or modem line*\ 
\ **Help**\ 
 \ *The ISDN identifies a ISDN or Modem line number.*\ 

Ship Address
------------
\ **Description**\ 
 \ *Business Partner Shipment Address*\ 
\ **Help**\ 
 \ *If the Ship Address is selected, the location is used to ship goods to a customer or receive goods from a vendor.*\ 

Invoice Address
---------------
\ **Description**\ 
 \ *Business Partner Invoice/Bill Address*\ 
\ **Help**\ 
 \ *If the Invoice Address is selected, the location is used to send invoices to a customer or receive invoices from a vendor.*\ 

Pay-From Address
----------------
\ **Description**\ 
 \ *Business Partner pays from that address and we'll send dunning letters there*\ 
\ **Help**\ 
 \ *If the Pay-From Address is selected, this location is the address the Business Partner pays from and where dunning letters will be sent to.*\ 

Remit-To Address
----------------
\ **Description**\ 
 \ *Business Partner payment address*\ 
\ **Help**\ 
 \ *If the Remit-To Address is selected, the location is used to send payments to the vendor.*\ 

Sales Region
------------
\ **Description**\ 
 \ *Sales coverage region*\ 
\ **Help**\ 
 \ *The Sales Region indicates a specific area of sales coverage.*\ 

Contact (User)
--------------
\ **Description**\ 
 \ *Maintain User within the system - Internal or Business Partner Contact*\ 
\ **Help**\ 
 \ *The User identifies a unique user in the system. This could be an internal user or a business partner contact*\ 

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

Business Partner
----------------
\ **Description**\ 
 \ *Identifies a Business Partner*\ 
\ **Help**\ 
 \ *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

Description
-----------
\ **Description**\ 
 \ *Optional short description of the record*\ 
\ **Help**\ 
 \ *A description is limited to 255 characters.*\ 

Comments
--------
\ **Description**\ 
 \ *Comments or additional information*\ 
\ **Help**\ 
 \ *The Comments field allows for free form entry of additional information.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

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

Greeting
--------
\ **Description**\ 
 \ *Greeting to print on correspondence*\ 
\ **Help**\ 
 \ *The Greeting identifies the greeting to print on correspondence.*\ 

Partner Location
----------------
\ **Description**\ 
 \ *Identifies the (ship from) address for this Business Partner*\ 
\ **Help**\ 
 \ *The Partner address indicates the location of a Business Partner*\ 

Title
-----
\ **Description**\ 
 \ *Name this entity is referred to as*\ 
\ **Help**\ 
 \ *The Title indicates the name that an entity is referred to as.*\ 

Birthday
--------
\ **Description**\ 
 \ *Birthday or Anniversary day*\ 
\ **Help**\ 
 \ *Birthday or Anniversary day*\ 

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

Notification Type
-----------------
\ **Description**\ 
 \ *Type of Notifications*\ 
\ **Help**\ 
 \ *Emails or Notification sent out for Request Updates, etc.*\ 

Position
--------
\ **Description**\ 
 \ *Job Position*\ 

Full BP Access
--------------
\ **Description**\ 
 \ *The user/contact has full access to Business Partner information and resources*\ 
\ **Help**\ 
 \ *If selected, the user has full access to the Business Partner (BP) information (Business Documents like Orders, Invoices - Requests) or resources (Assets, Downloads). If you deselect it, the user has no access rights unless, you explicitly grant it in tab "BP Access"*\ 

EMail Verify
------------
\ **Description**\ 
 \ *Date Email was verified*\ 

Verification Info
-----------------
\ **Description**\ 
 \ *Verification information of EMail Address*\ 
\ **Help**\ 
 \ *The field contains additional information how the EMail Address has been verified*\ 

Last Contact
------------
\ **Description**\ 
 \ *Date this individual was last contacted*\ 
\ **Help**\ 
 \ *The Last Contact indicates the date that this Business Partner Contact was last contacted.*\ 

Last Result
-----------
\ **Description**\ 
 \ *Result of last contact*\ 
\ **Help**\ 
 \ *The Last Result identifies the result of the last contact made.*\ 

License Assignment
------------------
\ **Description**\ 
 \ *License Assignment*\ 

.. note::
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

Driver
------

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

License
-------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Requirement Assignment
----------------------
\ **Description**\ 
 \ *Requirement Assignment*\ 

.. note::
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

Driver
------

Sequence
--------
\ **Description**\ 
 \ *Method of ordering records; lowest number comes first*\ 
\ **Help**\ 
 \ *The Sequence indicates the order of records*\ 

Transport Requirement
---------------------

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Valid
-----
\ **Description**\ 
 \ *Element is valid*\ 
\ **Help**\ 
 \ *The element passed the validation check*\ 
