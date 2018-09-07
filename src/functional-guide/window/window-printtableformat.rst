
.. _functional-guide/window/window-printtableformat:

==================
Print Table Format
==================

Define Report Table Format

Help
====
The Print Table Format lets you define how table header, etc. is printed. Please note that the Report Table FOrmat is cached to improve performance.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

Print Table Format
------------------
\ **Description**\ 
 \ *Define Report Table Format*\ 
\ **Help**\ 
 \ *The Print Table Format lets you define how table header, etc. is printed. If you leave the entries empty, the default colors and fonts are used:
Fonts are based on the Font used in the Report; Page Header and Table Header will be bold, the Function Font is Bold-Italic, the Footer Font is two points smaller, the Parameter Font is Italic.*\ 

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

Default
-------
\ **Description**\ 
 \ *Default value*\ 
\ **Help**\ 
 \ *The Default Checkbox indicates if this record will be used as a default value.*\ 

Header Row Color
----------------
\ **Description**\ 
 \ *Foreground color if the table header row*\ 
\ **Help**\ 
 \ *Table header row foreground color*\ 

Header Row BG Color
-------------------
\ **Description**\ 
 \ *Background color of header row*\ 
\ **Help**\ 
 \ *Table header row background color*\ 

Header Row Font
---------------
\ **Description**\ 
 \ *Header row Font*\ 
\ **Help**\ 
 \ *Font of the table header row*\ 

Multi Line Header
-----------------
\ **Description**\ 
 \ *Print column headers on mutliple lines if necessary.*\ 
\ **Help**\ 
 \ *If selected, column header text will wrap onto the next line -- otherwise the text will be truncated.*\ 

Paint Header Lines
------------------
\ **Description**\ 
 \ *Paint Lines over/under the Header Line*\ 
\ **Help**\ 
 \ *If selected, a line is painted above and below the header line using the stroke information*\ 

Header Line Color
-----------------
\ **Description**\ 
 \ *Table header row line color*\ 
\ **Help**\ 
 \ *Color of the table header row lines*\ 

Header Stroke Type
------------------
\ **Description**\ 
 \ *Type of the Header Line Stroke*\ 
\ **Help**\ 
 \ *Type of the line printed*\ 

Header Stroke
-------------
\ **Description**\ 
 \ *Width of the Header Line Stroke*\ 
\ **Help**\ 
 \ *The width of the header line stroke (line thickness) in Points.*\ 

Paint Vertical Lines
--------------------
\ **Description**\ 
 \ *Paint vertical lines*\ 
\ **Help**\ 
 \ *Paint vertical table lines*\ 

Paint Horizontal Lines
----------------------
\ **Description**\ 
 \ *Paint horizontal lines*\ 
\ **Help**\ 
 \ *Paint horizontal table lines*\ 

Paint Boundary Lines
--------------------
\ **Description**\ 
 \ *Paint table boundary lines*\ 
\ **Help**\ 
 \ *Paint lines around table*\ 

Line Color
----------
\ **Description**\ 
 \ *Table line color*\ 

Line Stroke Type
----------------
\ **Description**\ 
 \ *Type of the Line Stroke*\ 
\ **Help**\ 
 \ *Type of the line printed*\ 

Line Stroke
-----------
\ **Description**\ 
 \ *Width of the Line Stroke*\ 
\ **Help**\ 
 \ *The width of the line stroke (line thickness) in Points.*\ 

Print Function Symbols
----------------------
\ **Description**\ 
 \ *Print Symbols for Functions (Sum, Average, Count)*\ 
\ **Help**\ 
 \ *If selected, print symbols - otherwise print names of the function*\ 

Function Color
--------------
\ **Description**\ 
 \ *Function Foreground Color*\ 
\ **Help**\ 
 \ *Foreground color of a function row*\ 

Function BG Color
-----------------
\ **Description**\ 
 \ *Function Background Color*\ 
\ **Help**\ 
 \ *Background color of a function row*\ 

Function Font
-------------
\ **Description**\ 
 \ *Function row Font*\ 
\ **Help**\ 
 \ *Font of the function row*\ 

Image attached
--------------
\ **Description**\ 
 \ *The image to be printed is attached to the record*\ 
\ **Help**\ 
 \ *The image to be printed is stored in the database as attachment to this record. The image can be a gif, jpeg or png.*\ 

Image URL
---------
\ **Description**\ 
 \ *URL of  image*\ 
\ **Help**\ 
 \ *URL of image; The image is not stored in the database, but retrieved at runtime. The image can be a gif, jpeg or png.*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 
