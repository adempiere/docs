
.. _functional-guide/window/window-language:

========
Language
========

Maintain Languages

Help
====
The Language Window allows you to define multiple parallel language for users. This allows users to access the same data but have the windows, tabs and fields appear in different languages.
If a language is a System Language, you can change the User Interface to this language (after translation).  Otherwise the language is only used for printing documents.

For the language code, we suggest using the Java convention of country and language (e.g. fr_CN - Canadian French).

Verify the translation creates missing translation records. Start this process after creating a new language.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Language
--------
\ **Description**\ 
 \ *System and User Languages*\ 
\ **Help**\ 
 \ *If you want to add an additional User Interface language, select "System Language". Otherwise, the system allows you to just translate elements for printing documents.*\ 

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

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Name
----
\ **Description**\ 
 \ *Alphanumeric identifier of the entity*\ 
\ **Help**\ 
 \ *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*\ 

ISO Language Code
-----------------
\ **Description**\ 
 \ *Lower-case two-letter ISO-3166 code - http://www.ics.uci.edu/pub/ietf/http/related/iso639.txt*\ 
\ **Help**\ 
 \ *The ISO Language Code indicates the standard ISO code for a language in lower case.  Information can be found at http://www.ics.uci.edu/pub/ietf/http/related/iso639.txt*\ 

ISO Country Code
----------------
\ **Description**\ 
 \ *Upper-case two-letter alphanumeric ISO Country code according to ISO 3166-1 - http://www.chemie.fu-berlin.de/diverse/doc/ISO_3166.html*\ 
\ **Help**\ 
 \ *For details - http://www.din.de/gremien/nas/nabd/iso3166ma/codlstp1.html or - http://www.unece.org/trade/rec/rec03en.htm*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Base Language
-------------
\ **Description**\ 
 \ *The system information is maintained in this language*\ 

System Language
---------------
\ **Description**\ 
 \ *The screens, etc. are maintained in this Language*\ 
\ **Help**\ 
 \ *Select, if you want to have translated screens available in this language.  Please notify your system administrator to run the language maintenance scripts to enable the use of this language.  If the language is not supplied, you can translate the terms yourself.*\ 

Date Pattern
------------
\ **Description**\ 
 \ *Java Date Pattern*\ 
\ **Help**\ 
 \ *Option Date pattern in Java notation. Examples: dd.MM.yyyy - dd/MM/yyyy If the pattern for your language is not correct, please create a Adempiere support request with the correct information*\ 

Time Pattern
------------
\ **Description**\ 
 \ *Java Time Pattern*\ 
\ **Help**\ 
 \ *Option Time pattern in Java notation. Examples: "hh:mm:ss aaa z" - "HH:mm:ss"
If the pattern for your language is not correct, please create a Adempiere support request with the correct information*\ 

Decimal Point
-------------
\ **Description**\ 
 \ *The number notation has a decimal point (no decimal comma)*\ 
\ **Help**\ 
 \ *If selected, Numbers are printed with a decimal point "." - otherwise with a decimal comma ",".  The thousand separator is the opposite.
If the pattern for your language is not correct, please create a Adempiere support request with the correct information*\ 

Language Maintenance
--------------------
\ **Description**\ 
 \ *Maintain language translation in system*\ 
\ **Help**\ 
 \ *You can Add Missing Translation entries (required after activating an additional System Language) - Delete Translation Records - or Re-Create the translation Records (first delete and add missing entries).
Note that Adding the Missing Translation records creates them by copying the System Language (English).  You would apply the Language Pack after that process.  Run Syncronize Terminology after importing the translation.*\ 
