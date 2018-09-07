
.. _functional-guide/smart-browse/browserorder:

=============
Browser Order
=============

Smart Browser allows for a selection to be processed

.. seealso::
    :ref:`functional-guideprocess-c_orderselection`


.. note::
    The Records Deletable checkbox indicates if a record can be deleted from the database.  If records cannot be deleted, you can only deselect the Active flag
Flag to indicate if is collapsible by default
Allow define if a Browser is execute by default
Show totals for the column  of amount type.

Fields
======


======================  ===========================================================================================================  =========  ==============  ========  =========  =========
Name                    Description                                                                                                  Displayed  Query Criteria  Order By  Read Only  Mandatory
======================  ===========================================================================================================  =========  ==============  ========  =========  =========
Freight Category        Category of the Freight                                                                                      No         Yes             No        Yes        No       
Price List              Unique identifier of a Price List                                                                            No         Yes             No        Yes        No       
Invoice Location        Business Partner Location for invoicing                                                                      No         Yes             No        Yes        No       
Order                   Order                                                                                                        Yes        Yes             No        Yes        No       
Organization            Organizational entity within client                                                                          Yes        Yes             No        Yes        No       
Warehouse               Storage Warehouse and Service Point                                                                          Yes        Yes             No        Yes        No       
Document Type           Document type or rules                                                                                       Yes        Yes             No        Yes        No       
Document No             Document sequence number of the document                                                                     Yes        Yes             No        Yes        No       
Order Reference         Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner                          Yes        Yes             No        Yes        No       
Business Partner        Identifies a Business Partner                                                                                Yes        Yes             No        Yes        No       
Credit Status           Business Partner Credit Status                                                                               Yes        Yes             No        Yes        No       
Company Agent           Company Agent                                                                                                Yes        No              No        Yes        No       
Date Ordered            Date of Order                                                                                                Yes        Yes             No        Yes        No       
Date Promised           Date Order was promised                                                                                      Yes        Yes             No        No         No       
Order Type              Type of Order: MRP records grouped by source (Sales Order, Purchase Order, Distribution Order, Requisition)  Yes        Yes             No        Yes        No       
Sales Transaction       This is a Sales Transaction                                                                                  Yes        Yes             No        Yes        No       
Currency                The Currency for this record                                                                                 Yes        Yes             No        Yes        No       
Total Lines             Total of all document lines                                                                                  Yes        No              No        Yes        No       
Grand Total             Total amount of document                                                                                     Yes        Yes             No        Yes        No       
User/Contact            User within the system - Internal or Business Partner Contact                                                Yes        No              No        Yes        No       
Business Partner Group  Business Partner Group                                                                                       Yes        Yes             No        Yes        No       
Partner Location        Identifies the (ship to) address for this Business Partner                                                   Yes        No              No        Yes        No       
Invoice Partner         Business Partner to be invoiced                                                                              Yes        Yes             No        Yes        No       
Invoice Contact         Business Partner Contact for invoicing                                                                       Yes        No              No        Yes        No       
Document Status         The current status of the document                                                                           Yes        Yes             No        Yes        No       
Invoice Rule            Frequency and method of invoicing                                                                            Yes        Yes             No        Yes        No       
Payment Term            The terms of Payment (timing, discount)                                                                      Yes        Yes             No        Yes        No       
Payment Rule            How you pay the invoice                                                                                      Yes        Yes             No        Yes        No       
Priority                Priority of a document                                                                                       Yes        Yes             No        Yes        No       
Delivery Rule           Defines the timing of Delivery                                                                               Yes        Yes             No        Yes        No       
Delivery Via            How the order will be delivered                                                                              Yes        Yes             No        Yes        No       
Shipper                 Method or manner of product delivery                                                                         Yes        Yes             No        Yes        No       
Credit Approved         Credit  has been approved                                                                                    Yes        Yes             No        Yes        No       
Approved                Indicates if this document requires approval                                                                 Yes        Yes             No        Yes        No       
Delivered                                                                                                                            Yes        Yes             No        Yes        No       
Invoiced                Is this invoiced?                                                                                            Yes        Yes             No        Yes        No       
Campaign                Marketing Campaign                                                                                           Yes        Yes             No        Yes        No       
Activity                Business Activity                                                                                            Yes        Yes             No        Yes        No       
Project                 Financial Project                                                                                            Yes        Yes             No        Yes        No       
POS Terminal            Point of Sales Terminal                                                                                      Yes        Yes             No        Yes        No       
======================  ===========================================================================================================  =========  ==============  ========  =========  =========
