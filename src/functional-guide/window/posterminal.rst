
.. _functional-guide/window/posterminal:

============
POS Terminal
============

Maintain your Point of Sales Terminal

Help
====
The POS Terminal defines the defaults and functions available for the POS Form

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

POS Terminal
------------
\ **Description**\ 
 \ *Point of Sales Terminal*\ 
\ **Help**\ 
 \ *The POS Terminal defines the defaults and functions available for the POS Form*\ 

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

Comment/Help
------------
\ **Description**\ 
 \ *Comment or Hint*\ 
\ **Help**\ 
 \ *The Help field contains a hint, comment or help about the use of this item.*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Auto Logout Delay
-----------------
\ **Description**\ 
 \ *Automatically logout if terminal inactive for this period*\ 
\ **Help**\ 
 \ *Measured in seconds, zero for no automatic logout*\ 

Price List
----------
\ **Description**\ 
 \ *Unique identifier of a Price List*\ 
\ **Help**\ 
 \ *Price Lists are used to determine the pricing, margin and cost of items purchased or sold.*\ 

Modify Price
------------
\ **Description**\ 
 \ *Allow modifying the price*\ 
\ **Help**\ 
 \ *Allow modifying the price for products with a non zero price*\ 

Cash Book
---------
\ **Description**\ 
 \ *Cash Book for recording petty cash transactions*\ 
\ **Help**\ 
 \ *The Cash Book identifies a unique cash book.  The cash book is used to record cash transactions.*\ 

Template B.Partner
------------------
\ **Description**\ 
 \ *Business Partner used for creating new Business Partners on the fly*\ 
\ **Help**\ 
 \ *When creating a new Business Partner from the Business Partner Search Field (right-click: Create), the selected business partner is used as a template, e.g. to define price list, payment terms, etc.*\ 

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

Transfer Cash trx to
--------------------
\ **Description**\ 
 \ *Bank Account on which to transfer all Cash transactions*\ 

Document Type
-------------
\ **Description**\ 
 \ *Document type or rules*\ 
\ **Help**\ 
 \ *The Document Type determines document sequence and processing rules*\ 

Invoice Rule
------------
\ **Description**\ 
 \ *Frequency and method of invoicing*\ 
\ **Help**\ 
 \ *The Invoice Rule defines how a Business Partner is invoiced and the frequency of invoicing.*\ 

Warehouse
---------
\ **Description**\ 
 \ *Storage Warehouse and Service Point*\ 
\ **Help**\ 
 \ *The Warehouse identifies a unique Warehouse where products are stored or Services are provided.*\ 

Delivery Rule
-------------
\ **Description**\ 
 \ *Defines the timing of Delivery*\ 
\ **Help**\ 
 \ *The Delivery Rule indicates when an order should be delivered. For example should the order be delivered when the entire order is complete, when a line is complete or as the products become available.*\ 

POS Key Layout
--------------
\ **Description**\ 
 \ *POS Function Key Layout*\ 
\ **Help**\ 
 \ *POS Function Key Layout*\ 

Enable POS Product Lookup
-------------------------
\ **Description**\ 
 \ *Allows product lookup in order to show search key , name , quantity available , standard price and list price for selecting a product*\ 

On Screen Keyboard layout
-------------------------
\ **Description**\ 
 \ *The key layout to use for on screen keyboard for text fields.*\ 
\ **Help**\ 
 \ *If empty, the on screen keyboard will not be used.*\ 

On Screen Number Pad layout
---------------------------
\ **Description**\ 
 \ *The key layout to use for on screen number pad for numeric fields.*\ 
\ **Help**\ 
 \ *If empty, the on screen numberpad will not be used.*\ 

Printer Name
------------
\ **Description**\ 
 \ *Name of the Printer*\ 
\ **Help**\ 
 \ *Internal (Operating System) Name of the Printer; Please mote that the printer name may be different on different clients. Enter a printer name, which applies to ALL clients (e.g. printer on a server). 
If none is entered, the default printer is used. You specify your default printer when you log in. You can also change the default printer in Preferences.*\ 

CashDrawer
----------

Electronic Scales
-----------------
\ **Description**\ 
 \ *Allows to define path for Device Electronic Scales e.g. /dev/ttyS0/*\ 

Measure Request Code
--------------------
\ **Description**\ 
 \ *String for  taking measurement from Device Electronic Scales*\ 

POS Required PIN
----------------
\ **Description**\ 
 \ *Indicates that a Supervisor Pin is mandatory to execute some tasks e.g. (Change Price , Offer Discount , Delete POS Line)*\ 

PIN Entry Timeout
-----------------
\ **Description**\ 
 \ *PIN Entry Timeout - the amount of time from initial display until the PIN entry dialog times out, in milliseconds.*\ 

Ticket Handler Class Name
-------------------------
\ **Description**\ 
 \ *Java Classname for Ticket Handler*\ 
\ **Help**\ 
 \ *The Classname identifies the Java classname used by this report or process.*\ 
