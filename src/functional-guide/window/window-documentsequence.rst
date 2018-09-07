
.. _functional-guide/window/window-documentsequence:

=================
Document Sequence
=================

Maintain System and Document Sequences

Help
====
The Sequence Window defines how document numbers will be sequenced.
Change the way document numbers are generated. You may add a prefix or a suffix or change the current number.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Sequence
--------
\ **Description**\ 
 \ *Sequence Definition*\ 
\ **Help**\ 
 \ *The Sequence Tab defines the numeric sequencing to use for documents.  These can also include a alpha suffix and / or prefix.*\ 

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

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Auto numbering
--------------
\ **Description**\ 
 \ *Automatically assign the next number*\ 
\ **Help**\ 
 \ *The Auto Numbering checkbox indicates if the system will assign the next number automatically.*\ 

Used for Record ID
------------------
\ **Description**\ 
 \ *The document number  will be used as the record key*\ 
\ **Help**\ 
 \ *The Used for Record ID checkbox indicates if the document id will be used as the key to the record*\ 

Value Format
------------
\ **Description**\ 
 \ *Format of the value; Can contain fixed format elements, Variables: "_lLoOaAcCa09"*\ 
\ **Help**\ 
 \ *\ **Validation elements:**\ 
 	(Space) any character
_	Space (fixed character)
l	any Letter a..Z NO space
L	any Letter a..Z NO space converted to upper case
o	any Letter a..Z or space
O	any Letter a..Z or space converted to upper case
a	any Letters & Digits NO space
A	any Letters & Digits NO space converted to upper case
c	any Letters & Digits or space
C	any Letters & Digits or space converted to upper case
0	Digits 0..9 NO space
9	Digits 0..9 or space

Example of format "(000)_000-0000"*\ 

Increment
---------
\ **Description**\ 
 \ *The number to increment the last document number by*\ 
\ **Help**\ 
 \ *The Increment indicates the number to increment the last document number by to arrive at the next sequence number*\ 

Current Next
------------
\ **Description**\ 
 \ *The next number to be used*\ 
\ **Help**\ 
 \ *The Current Next indicates the next number to use for this document*\ 

Decimal Pattern
---------------
\ **Description**\ 
 \ *Java Decimal Pattern*\ 
\ **Help**\ 
 \ *Option Decimal pattern in Java notation. Examples: 0000 will format 23 to 0023*\ 

Restart sequence every Year
---------------------------
\ **Description**\ 
 \ *Restart the sequence with Start on every 1/1*\ 
\ **Help**\ 
 \ *The Restart Sequence Every Year checkbox indicates that the documents sequencing should return to the starting number on the first day of the year.*\ 

Start No
--------
\ **Description**\ 
 \ *Starting number/position*\ 
\ **Help**\ 
 \ *The Start Number indicates the starting position in the line or field number in the line*\ 

Date Column
-----------
\ **Description**\ 
 \ *Fully qualified date column*\ 
\ **Help**\ 
 \ *The Date Column indicates the date to be used when calculating this measurement*\ 

Prefix
------
\ **Description**\ 
 \ *Prefix before the sequence number*\ 
\ **Help**\ 
 \ *The Prefix indicates the characters to print in front of the document number.*\ 

Suffix
------
\ **Description**\ 
 \ *Suffix after the number*\ 
\ **Help**\ 
 \ *The Suffix indicates the characters to append to the document number.*\ 

Activate Audit
--------------
\ **Description**\ 
 \ *Activate Audit Trail of what numbers are generated*\ 
\ **Help**\ 
 \ *The Activate Audit checkbox indicates if an audit trail of numbers generated will be kept.*\ 
