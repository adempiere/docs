
.. _functional-guide/process/process-m_forecastgenerateforecast:

=================
Generate Forecast
=================

This process allows to generate a forecast based on the forecast simulation calculation.

Help
====
The process uses the resulting simulation values ​ to generate a new forecast.


\ **Action Type of the forecast:**\   It Indicates how the forecast will be generated


If the action type is \ **"Replace"**\  all lines of this forecast are going to be  eliminated and will be generated again, based on the simulation products and the selection criteria.


If the action type  is \ **"Merge"**\  all lines of this forecast will be combined, based on the unique combination of product, warehouse and period. Therefore, if the combination exists, the forecast quantities are accumulated.


\ **The Load Type of forecast: **\ Indicates which date of the period will be used to determine the forecast line promised date.


\ **Options:**\ 


\ **To Use the Period Start Date: **\ The due date is set  based on the period start date 
\ **To Use the Period End Date:  **\ The due date is set based on the period end date.


\ **Days after the due date: **\  Indicates the number of days to be added or subtracted to the due date. If the value is negative, the days are subtracted.


\ **Selection Criteria:**\ 

It is possible to use the category, classification, class and group of the product to get the products to be included in the new forecast.

Parameters
==========

Forecast Run
------------
\ **Description**\ 
 \ *Create the forecast simulation based on the forecast definition*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Forecast
--------
\ **Description**\ 
 \ *Material Forecast*\ 
\ **Help**\ 
 \ *Material Forecast*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Date Promised
-------------
\ **Description**\ 
 \ *Date Order was promised*\ 
\ **Help**\ 
 \ *The Date Promised indicates the date, if any, that an Order was promised for.*\ 

.. note::
    The field must have a value for the record to be saved to the database.
The Range checkbox indicates that this parameter is a range of values.

Forecast Action Type
--------------------
\ **Description**\ 
 \ *Forecast is replaced or combined*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Forecast Load Type
------------------
\ **Description**\ 
 \ *Load Type indicated that period date is use to create the forecast line.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Days after due date
-------------------
\ **Description**\ 
 \ *Days after due date to dun (if negative days until due)*\ 
\ **Help**\ 
 \ *The Days After Due Date indicates the number of days after the payment due date to initiate dunning. If the number is negative, it includes not the not due invoices.*\ 

Sales Representative
--------------------
\ **Description**\ 
 \ *Sales Representative or Company Agent*\ 
\ **Help**\ 
 \ *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*\ 

Product
-------
\ **Description**\ 
 \ *Product, Service, Item*\ 
\ **Help**\ 
 \ *Identifies an item which is either purchased or sold in this organization.*\ 

Product Category
----------------
\ **Description**\ 
 \ *Category of a Product*\ 
\ **Help**\ 
 \ *Identifies the category which this product belongs to.  Product categories are used for pricing and selection.*\ 

Product Classification
----------------------
\ **Description**\ 
 \ *Classification of a Product*\ 
\ **Help**\ 
 \ *Identifies the classification which this product belongs to.*\ 

Product Class
-------------
\ **Description**\ 
 \ *Class of a Product*\ 
\ **Help**\ 
 \ *Identifies the Class which this product belongs to*\ 

Product Group
-------------
\ **Description**\ 
 \ *Group of a Product*\ 
\ **Help**\ 
 \ *Identifies the Group which this product belongs to.*\ 
