
.. _functional-guide/window/window-countryregionandcity:

=======================
Country Region and City
=======================

Maintain Countries Regions and Cities

Help
====
The Countries, Regions and Cities Window defines the different entities that can be used in any address field.  It defines the format of the address as well as associating Regions with Countries and Cities with Regions or Countries. 
You would define Countries usually only on System level.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Country
-------
\ **Description**\ 
 \ *Define Country*\ 
\ **Help**\ 
 \ *The Country Tab defines any country in which you do business.  Values entered here are referenced in location records for Business Partners.*\ 

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

ISO Country Code
----------------
\ **Description**\ 
 \ *Upper-case two-letter alphanumeric ISO Country code according to ISO 3166-1 - http://www.chemie.fu-berlin.de/diverse/doc/ISO_3166.html*\ 
\ **Help**\ 
 \ *For details - http://www.din.de/gremien/nas/nabd/iso3166ma/codlstp1.html or - http://www.unece.org/trade/rec/rec03en.htm*\ 

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

Country has Region
------------------
\ **Description**\ 
 \ *Country contains Regions*\ 
\ **Help**\ 
 \ *The Country has Region checkbox is selected if the Country being defined is divided into regions.  If this checkbox is selected, the Region Tab is accessible.*\ 

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Address Print Format
--------------------
\ **Description**\ 
 \ *Format for printing this Address*\ 
\ **Help**\ 
 \ *The Address Print format defines the format to be used when this address prints.  The following notations are used: @C@=City  @P@=Postal  @A@=PostalAdd  @R@=Region*\ 

Reverse Address Lines
---------------------
\ **Description**\ 
 \ *Print Address in reverse Order*\ 
\ **Help**\ 
 \ *If NOT selected the sequence is Address 1, Address 2, Address 3, Address 4, City/Region/Postal, Country.
If selected the sequence is Country, City/Region/Postal, Address 4, Address 3, Address 2, Address 1.
The sequence of City/Region/Postal is determined by the address format.*\ 

Capture Sequence
----------------
\ **Help**\ 
 \ *The Capture Sequence defines the fields to be used when capturing an address on this country.  The following notations are used: @CO@=Country, @C@=City, @P@=Postal, @A@=PostalAdd, @R@=Region, @A1@=Address 1 to @A4@=Address 4.  Country is always mandatory, add a bang ! to make another field mandatory, for example @C!@ makes city mandatory, @A1!@ makes Address 1 mandatory.*\ 

Local Address Format
--------------------
\ **Description**\ 
 \ *Format for printing this Address locally*\ 
\ **Help**\ 
 \ *The optional Local Address Print format defines the format to be used when this address prints for the Country.  If defined, this format is used for printing the address for the country rather then the standard address format.
 The following notations are used: @C@=City  @P@=Postal  @A@=PostalAdd  @R@=Region*\ 

Reverse Local Address Lines
---------------------------
\ **Description**\ 
 \ *Print Local Address in reverse Order*\ 
\ **Help**\ 
 \ *If NOT selected the local sequence is Address 1, Address 2, Address 3, Address 4, City/Region/Postal, Country.
If selected the local sequence is Country, City/Region/Postal, Address 4, Address 3, Address 2, Address 1.
The sequence of City/Region/Postal is determined by the local address format.*\ 

Postal Code Format
------------------
\ **Description**\ 
 \ *Format of the postal code; Can contain fixed format elements, Variables: "_lLoOaAcCa09"*\ 
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

Additional Postal code
----------------------
\ **Description**\ 
 \ *Has Additional Postal Code*\ 
\ **Help**\ 
 \ *The Additional Postal Code checkbox indicates if this address uses an additional Postal Code.  If it is selected an additional field displays for entry of the additional Postal Code.*\ 

Additional Postal Format
------------------------
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

Phone Format
------------
\ **Description**\ 
 \ *Format of the phone; Can contain fixed format elements, Variables: "_lLoOaAcCa09"*\ 
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

Media Size
----------
\ **Description**\ 
 \ *Java Media Size*\ 
\ **Help**\ 
 \ *The Java Media Size. Example: "MediaSize.ISO.A4" (the package javax.print.attribute.standard is assumed). If you define your own media size, use the fully qualified name.
If the pattern for your language is not correct, please create a Adempiere support request with the correct information*\ 

Bank Routing No Format
----------------------
\ **Description**\ 
 \ *Format of the Bank Routing Number*\ 

Bank Account No Format
----------------------
\ **Description**\ 
 \ *Format of the Bank Account*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

Use Postcode Lookup
-------------------
\ **Description**\ 
 \ *Does this country have a post code web service*\ 
\ **Help**\ 
 \ *Enable the IsPostcodeLookup if you wish to configure a post code lookup web service*\ 

Allow Cities out of List
------------------------
\ **Description**\ 
 \ *A flag to allow cities, currently not in the list, to be entered*\ 

Lookup URL
----------
\ **Description**\ 
 \ *The URL of the web service that the plugin connects to in order to retrieve postcode data*\ 
\ **Help**\ 
 \ *Enter the URL of the web service that the plugin connects to in order to retrieve postcode data*\ 

Lookup Client ID
----------------
\ **Description**\ 
 \ *The ClientID or Login submitted to the Lookup URL*\ 
\ **Help**\ 
 \ *Enter the ClientID or Login for your account provided by the post code web service provider*\ 

Lookup Password
---------------
\ **Description**\ 
 \ *The password submitted to the Lookup URL*\ 
\ **Help**\ 
 \ *Enter the password for your account provided by the post code web service provider*\ 

Lookup ClassName
----------------
\ **Description**\ 
 \ *The class name of the postcode lookup plugin*\ 
\ **Help**\ 
 \ *Enter the class name of the post code lookup plugin for your postcode web service provider*\ 

Translation
-----------

.. note::
    The Translation Tab checkbox indicate if a tab contains translation information. To display translation information, enable this in Tools>Preference.

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

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

Language
--------
\ **Description**\ 
 \ *Language for this entity*\ 
\ **Help**\ 
 \ *The Language identifies the language to use for display and formatting*\ 

Active
------
\ **Description**\ 
 \ *The record is active in the system*\ 
\ **Help**\ 
 \ *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*\ 

Translated
----------
\ **Description**\ 
 \ *This column is translated*\ 
\ **Help**\ 
 \ *The Translated checkbox indicates if this column is translated.*\ 

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

Region
------
\ **Description**\ 
 \ *Name of the Region*\ 
\ **Help**\ 
 \ *The Region Name defines the name that will print when this region is used in a document.*\ 

Region
------
\ **Description**\ 
 \ *Define Regions*\ 
\ **Help**\ 
 \ *The Region Tab  defines a Region within a Country.  This tab is enabled only if the Has Region checkbox is selected for the Country.*\ 

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

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

City
----
\ **Description**\ 
 \ *Define Cities*\ 
\ **Help**\ 
 \ *The Cities Tab defines Cities within a Country or Region.  Cities entered here are not referenced when entering the address.*\ 

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

Country
-------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *The Country defines a Country.  Each Country must be defined before it can be used in any document.*\ 

Region
------
\ **Description**\ 
 \ *Identifies a geographical Region*\ 
\ **Help**\ 
 \ *The Region identifies a unique Region for this Country.*\ 

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

ZIP
---
\ **Description**\ 
 \ *Postal code*\ 
\ **Help**\ 
 \ *The Postal Code or ZIP identifies the postal code for this entity's address.*\ 

Area Code
---------
\ **Description**\ 
 \ *Phone Area Code*\ 
\ **Help**\ 
 \ *Phone Area Code*\ 

Locode
------
\ **Description**\ 
 \ *Location code - UN/LOCODE*\ 
\ **Help**\ 
 \ *UN/Locode is a combination of a 2-character country code and a 3-character location code, e.g. BEANR is known as the city of Antwerp (ANR) which is located in Belgium (BE).
See: http://www.unece.org/cefact/locode/service/main.htm*\ 

Coordinates
-----------
\ **Description**\ 
 \ *Location coordinate*\ 
\ **Help**\ 
 \ *This column contains the geographical coordinates (latitude/longitude) of the location.
In order to avoid unnecessary use of non-standard characters and space, the following standard presentation is used:
0000N 00000W 0000S 00000E 
where the two last digits refer to minutes and the two or three first digits indicate the degrees*\ 
