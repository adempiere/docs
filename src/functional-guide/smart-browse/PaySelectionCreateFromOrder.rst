
.. _smart-browse-payselectioncreatefromorder:

=================
Create from Order
=================

Create Payment Selection lines from Orders selected

.. seealso::
    :ref:`window-purchaseorder`


.. seealso::
    :ref:`process-sbp_payselectioncreatefromorder`


.. note::
    Flag to indicate if is collapsible by default
Show totals for the column  of amount type.

Fields
======


=================  ========================================  =========  ==============  ========  =========  =========
Name               Description                               Displayed  Query Criteria  Order By  Read Only  Mandatory
=================  ========================================  =========  ==============  ========  =========  =========
Order              Order                                     Yes        Yes             No        Yes        No       
Business Partner   Identifies a Business Partner             Yes        Yes             No        Yes        No       
Document Type      Document type or rules                    Yes        Yes             No        Yes        No       
Date Ordered       Date of Order                             Yes        Yes             Yes       Yes        No       
Date Promised      Date Order was promised                   Yes        Yes             No        Yes        No       
Document No        Document sequence number of the document  Yes        No              No        Yes        No       
Payment Rule       How you pay the invoice                   Yes        Yes             No        Yes        No       
Currency           The Currency for this record              Yes        Yes             No        Yes        No       
Currency Type      Currency Conversion Rate Type             Yes        No              No        Yes        No       
Grand Total        Total amount of document                  Yes        No              No        Yes        No       
Converted Amount   Converted Amount                          Yes        No              No        Yes        No       
Payment amount     Amount being paid                         Yes        No              No        No         No       
Payment Term       The terms of Payment (timing, discount)   Yes        No              No        Yes        No       
Sales Transaction  This is a Sales Transaction               Yes        Yes             No        Yes        No       
Delivered                                                    Yes        No              No        Yes        No       
Description        Optional short description of the record  Yes        No              No        Yes        No       
=================  ========================================  =========  ==============  ========  =========  =========
