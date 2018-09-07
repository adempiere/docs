
.. _functional-guide/smart-browse/outboundordertorelease:

=========================
Outbound Order to Release
=========================

This Smart Browse allow select the Outbound Order to release the lines that need be pick.

Help
====
This process generates that Distribution Order to pick,   based on the warehouse rules

.. seealso::
    :ref:`functional-guidewindow-outboundorder`


.. seealso::
    :ref:`functional-guideprocess-wm_inoutboundprintreleasepicking`


.. note::
    Flag to indicate if is collapsible by default

Fields
======


=============================  ===================================================================================  =========  ==============  ========  =========  =========
Name                           Description                                                                          Displayed  Query Criteria  Order By  Read Only  Mandatory
=============================  ===================================================================================  =========  ==============  ========  =========  =========
Inbound & Outbound Order Line                                                                                       Yes        No              No        Yes        Yes      
Pick Date                      Date/Time when picked for Shipment                                                   Yes        Yes             No        Yes        No       
Ship Date                      Shipment Date/Time                                                                   Yes        Yes             No        Yes        No       
In & Out Bound Order                                                                                                Yes        Yes             No        Yes        No       
Document No                    Document sequence number of the document                                             No         Yes             No        Yes        No       
Document Type                  Document type or rules                                                               Yes        Yes             No        Yes        No       
Order Reference                Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner  No         Yes             No        Yes        No       
Sales Representative           Sales Representative or Company Agent                                                Yes        Yes             No        Yes        No       
Priority                       Priority of a document                                                               Yes        Yes             No        Yes        No       
Warehouse                      Storage Warehouse and Service Point                                                  Yes        Yes             No        Yes        No       
Delivery Rule                  Defines the timing of Delivery                                                       Yes        Yes             No        Yes        No       
Delivery Via                   How the order will be delivered                                                      No         Yes             No        Yes        No       
Shipper                        Method or manner of product delivery                                                 Yes        Yes             No        Yes        No       
Freight Cost Rule              Method for charging Freight                                                          Yes        Yes             No        Yes        No       
Tracking No                    Number to track the shipment                                                         No         Yes             No        Yes        No       
Product                        Product, Service, Item                                                               Yes        Yes             No        Yes        No       
Movement Quantity              Quantity of a product moved.                                                         Yes        No              No        Yes        No       
On Hand Quantity               On Hand Quantity                                                                     Yes        No              No        Yes        No       
Picked Qty                                                                                                          Yes        No              No        Yes        No       
Name                           Alphanumeric identifier of the entity                                                Yes        No              No        Yes        No       
Business Partner               Identifies a Business Partner                                                        Yes        Yes             No        Yes        No       
Sales Order Line               Sales Order Line                                                                     Yes        No              No        Yes        No       
=============================  ===================================================================================  =========  ==============  ========  =========  =========
