
.. _functional-guide/smart-browse/sbinvoicecreatefrom:

===================
Invoice Create From
===================

Create From Order / RMA / Invoice / Receipt in a Invoice

.. seealso::
    :ref:`functional-guideprocess-sbp_invoicecreatefrom`


.. note::
    Flag to indicate if is collapsible by default
Show totals for the column  of amount type.

Fields
======


==============================  =================================================  =========  ==============  ========  =========  =========
Name                            Description                                        Displayed  Query Criteria  Order By  Read Only  Mandatory
==============================  =================================================  =========  ==============  ========  =========  =========
Shipment/Receipt                Material Shipment Document                         No         Yes             No        Yes        Yes      
Create From Type                                                                   No         Yes             No        Yes        Yes      
Invoice                         Invoice Identifier                                 No         Yes             No        Yes        Yes      
RMA                             Return Material Authorization                      No         Yes             No        Yes        Yes      
Order                           Order                                              No         Yes             No        Yes        Yes      
Invoice Create From Identifier                                                     Yes        No              No        Yes        No       
Line No                         Unique line for this document                      Yes        No              Yes       Yes        No       
Document Date                   Date of the Document                               Yes        No              No        Yes        No       
Name                            Alphanumeric identifier of the entity              Yes        No              No        Yes        No       
Attribute Set Instance          Product Attribute Set Instance                     Yes        No              No        Yes        No       
Quantity                        The Quantity Entered is based on the selected UoM  Yes        No              No        No         No       
UOM                             Unit of Measure                                    Yes        No              No        Yes        No       
Movement Quantity               Quantity of a product moved.                       Yes        No              No        Yes        No       
Description                     Optional short description of the record           Yes        No              No        Yes        No       
Partner Product Key             Product Key of the Business Partner                Yes        No              No        Yes        No       
==============================  =================================================  =========  ==============  ========  =========  =========
