
.. _functional-guide/smart-browse/schedulingoftheactivities:

============================
Scheduling of the Activities
============================

Browser for schedule the start and end dates of the activities of manufacturing orders

.. seealso::
    :ref:`functional-guidewindow-activitycontrolreport`


.. seealso::
    :ref:`functional-guideprocess-pp_schedulingactivities`


Fields
======


============================  ================================================================================================  =========  ==============  ========  =========  =========
Name                          Description                                                                                       Displayed  Query Criteria  Order By  Read Only  Mandatory
============================  ================================================================================================  =========  ==============  ========  =========  =========
Manufacturing Order Activity  Workflow Node (activity), step or process                                                         Yes        No              No        Yes        No       
Work Center                   Work Center                                                                                       Yes        Yes             No        Yes        No       
Search Key                    Search key for the record in the format required - must be unique                                 No         Yes             No        Yes        No       
Milestone                                                                                                                       Yes        Yes             No        Yes        No       
Subcontracting                                                                                                                  Yes        Yes             No        Yes        No       
Activity Value                Search key for the record in the format required - must be unique                                 Yes        Yes             No        Yes        No       
Name                          Alphanumeric identifier of the entity                                                             Yes        No              No        Yes        No       
Priority                      Indicates if this request is of a high, medium or low priority.                                   Yes        Yes             No        Yes        No       
Date Promised                 Date Order was promised                                                                           Yes        Yes             No        Yes        No       
Start Schedule                Scheduled start date for this Order                                                               Yes        Yes             No        No         No       
Finish Schedule               Scheduled Finish date for this Order                                                              Yes        Yes             No        No         No       
Status                        The current status of the document                                                                Yes        No              No        Yes        No       
Duration Unit                 Unit of Duration                                                                                  Yes        No              No        Yes        No       
S. T. Req.                                                                                                                      Yes        No              No        Yes        No       
S. T. Real                                                                                                                      Yes        No              No        Yes        No       
Duration Req.                                                                                                                   Yes        No              No        Yes        No       
Duration Real                                                                                                                   Yes        No              No        Yes        No       
Document No                   Document sequence number of the document                                                          Yes        Yes             No        Yes        No       
Line No                       Unique line for this document                                                                     Yes        Yes             No        Yes        No       
Product                       Product, Service, Item                                                                            Yes        Yes             No        Yes        No       
Attribute Set Instance        Product Attribute Set Instance                                                                    Yes        No              No        Yes        No       
Ordered Quantity              Ordered Quantity                                                                                  Yes        No              No        Yes        No       
Overlap Units                 Overlap Units are number of units that must be completed before they are moved the next activity  Yes        No              No        Yes        No       
Qty Required                                                                                                                    Yes        No              No        Yes        No       
Delivered Quantity            Delivered Quantity                                                                                Yes        No              No        Yes        No       
Qty Reject                                                                                                                      Yes        No              No        Yes        No       
Scrap %                       Scrap % Quantity for this componet                                                                Yes        No              No        Yes        No       
============================  ================================================================================================  =========  ==============  ========  =========  =========
