
.. _functional-guide/smart-browse/mrpactionmessages:

===================
MRP Action Messages
===================

MRP Action Messages

Help
====


This browser allows to show the action messages created by the Materials Plan process, multiple selection criteria can be defined (Organization, Warehouse, Plant, Planner, Message, Order Type, Priority, Product, Scheduled Start Date)

To visualize the message detail you can click the zoom button. 

.. seealso::
    :ref:`functional-guidewindow-mrpnotice`


Fields
======


==============  ===========================================================================================================  =========  ==============  ========  =========  =========
Name            Description                                                                                                  Displayed  Query Criteria  Order By  Read Only  Mandatory
==============  ===========================================================================================================  =========  ==============  ========  =========  =========
Notice          System Notice                                                                                                Yes        No              No        Yes        Yes      
Organization    Organizational entity within client                                                                          Yes        Yes             No        Yes        No       
Warehouse       Storage Warehouse and Service Point                                                                          Yes        Yes             No        Yes        No       
Resource        Resource                                                                                                     Yes        Yes             No        Yes        No       
User/Contact    User within the system - Internal or Business Partner Contact                                                Yes        Yes             No        Yes        No       
Message         System Message                                                                                               Yes        Yes             No        Yes        No       
Text Message    Text Message                                                                                                 Yes        No              No        Yes        Yes      
Order Type      Type of Order: MRP records grouped by source (Sales Order, Purchase Order, Distribution Order, Requisition)  Yes        Yes             No        Yes        No       
Document No     Document sequence number of the document                                                                     Yes        No              No        Yes        Yes      
Priority        Indicates if this request is of a high, medium or low priority.                                              Yes        Yes             No        Yes        No       
Product         Product, Service, Item                                                                                       Yes        Yes             No        Yes        No       
Start Schedule  Scheduled start date for this Order                                                                          Yes        Yes             No        Yes        No       
Date Promised   Date Order was promised                                                                                      Yes        No              No        Yes        Yes      
Quantity        Quantity                                                                                                     Yes        No              No        Yes        Yes      
Is MPS          Indicates if this product is part of the master production schedule                                          Yes        No              No        Yes        Yes      
==============  ===========================================================================================================  =========  ==============  ========  =========  =========
