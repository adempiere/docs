
.. _smart-browse-paymentcreatefrominvoice:

========================================
Generate Payment (From Invoice Customer)
========================================

Create Payment Selection lines from Invoices selected

.. seealso::
    :ref:`window-invoicecustomer`


.. seealso::
    :ref:`process-sbp_paymentgeneratefrominvoice`


.. note::
    Flag to indicate if is collapsible by default
Show totals for the column  of amount type.

Fields
======


=================  =========================================================  =========  ==============  ========  =========  =========
Name               Description                                                Displayed  Query Criteria  Order By  Read Only  Mandatory
=================  =========================================================  =========  ==============  ========  =========  =========
Business Partner   Identifies a Business Partner                              No         Yes             No        Yes        Yes      
Only Discount      Include only invoices where we would get payment discount  No         Yes             No        Yes        No       
Only Due           Include only due invoices                                  No         Yes             No        Yes        No       
Order              Order                                                      No         Yes             No        Yes        No       
Currency           The Currency for this record                               No         Yes             No        No         Yes      
Invoice            Invoice Identifier                                         Yes        Yes             No        Yes        No       
Date Invoiced      Date printed on Invoice                                    Yes        Yes             Yes       Yes        No       
Due Date           Date when the payment is due                               Yes        Yes             Yes       Yes        No       
Days due           Number of days due (negative: due in number of days)       Yes        Yes             No        Yes        No       
Document No        Document sequence number of the document                   Yes        No              No        Yes        No       
Description        Optional short description of the record                   Yes        No              No        Yes        No       
Currency           The Currency for this record                               Yes        No              No        Yes        No       
Grand Total        Total amount of document                                   Yes        No              No        Yes        No       
Converted Amount   Converted Amount                                           Yes        No              No        Yes        No       
Discount Amount    Calculated amount of discount                              Yes        No              No        Yes        No       
Open Amount        Open item amount                                           Yes        No              No        Yes        No       
Payment amount     Amount being paid                                          Yes        No              No        No         No       
Currency Type      Currency Conversion Rate Type                              Yes        No              No        Yes        No       
Document Type      Document type or rules                                     Yes        Yes             No        Yes        No       
In Dispute         Document is in dispute                                     Yes        Yes             No        Yes        No       
Payment Rule       How you pay the invoice                                    Yes        Yes             No        Yes        No       
Payment Term       The terms of Payment (timing, discount)                    Yes        Yes             No        Yes        No       
=================  =========================================================  =========  ==============  ========  =========  =========
