
.. _functional-guide/window/systemcolor:

============
System Color
============

Maintain System Colors

Help
====
System colors are used for background and indicators

.. note::
    Beta functionality is not fully tested or completed.

Window Type
-----------
\ **Maintain**\ 

.. note::
    The Sales Transaction checkbox indicates if this item is a Sales Transaction.


Tabs
====

System Color
------------
\ **Description**\ 
 \ *System color for backgrounds and indicators*\ 

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

Color Type
----------
\ **Description**\ 
 \ *Color presentation for this color*\ 

Red
---
\ **Description**\ 
 \ *RGB value*\ 

2nd Red
-------
\ **Description**\ 
 \ *RGB value for second color*\ 

Green
-----
\ **Description**\ 
 \ *RGB value*\ 

2nd Green
---------
\ **Description**\ 
 \ *RGB value for second color*\ 

Blue
----
\ **Description**\ 
 \ *Color RGB blue value*\ 

2nd Blue
--------
\ **Description**\ 
 \ *RGB value for second color*\ 

Alpha
-----
\ **Description**\ 
 \ *Color Alpha value 0-255*\ 

2nd Alpha
---------
\ **Description**\ 
 \ *Alpha value for second color*\ 

Start Point
-----------
\ **Description**\ 
 \ *Start point of the gradient colors*\ 
\ **Help**\ 
 \ *The gradient starts at the start point (e.g. North). The repeat distance determines if and how often the gradient colors are repeated.  If starting from southern points, the upper color is actually at the button.*\ 

Repeat Distance
---------------
\ **Description**\ 
 \ *Distance in points to repeat gradient color - or zero*\ 
\ **Help**\ 
 \ *The gradient color is not repeated, if the value is zero. The distance is added to (or subtracted from) the starting point of the gradient.*\ 

Line Width
----------
\ **Description**\ 
 \ *Width of the lines*\ 

Line Distance
-------------
\ **Description**\ 
 \ *Distance between lines*\ 

Image
-----
\ **Description**\ 
 \ *Image or Icon*\ 
\ **Help**\ 
 \ *Images and Icon can be used to display supported graphic formats (gif, jpg, png).
You can either load the image (in the database) or point to a graphic via a URI (i.e. it can point to a resource, http address)*\ 

Image Alpha
-----------
\ **Description**\ 
 \ *Image Texture Composite Alpha*\ 
\ **Help**\ 
 \ *Composite Alpha factor for taint color.*\ 
