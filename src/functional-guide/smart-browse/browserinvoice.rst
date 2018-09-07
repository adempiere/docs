
.. _functional-guide/smart-browse/browserinvoice:

===============
Browser Invoice
===============

Smart Browser allows for a selection to be processed

.. seealso::
    :ref:`functional-guideprocess-c_invoiceselection`


.. note::
    The Records Deletable checkbox indicates if a record can be deleted from the database.  If records cannot be deleted, you can only deselect the Active flag
Flag to indicate if is collapsible by default
Allow define if a Browser is execute by default
Show totals for the column  of amount type.

Fields
======


======================  ===================================================================================  =========  ==============  ========  =========  =========
Name                    Description                                                                          Displayed  Query Criteria  Order By  Read Only  Mandatory
======================  ===================================================================================  =========  ==============  ========  =========  =========
Search Key              Search key for the record in the format required - must be unique                    No         Yes             No        Yes        No       
Sales Transaction       This is a Sales Transaction                                                          No         Yes             No        Yes        No       
Organization            Organizational entity within client                                                  Yes        Yes             No        Yes        No       
Invoice                 Invoice Identifier                                                                   Yes        Yes             No        Yes        No       
Document Type           Document type or rules                                                               Yes        Yes             No        Yes        No       
Document No             Document sequence number of the document                                             Yes        Yes             No        Yes        No       
Order Reference         Transaction Reference Number (Sales Order, Purchase Order) of your Business Partner  Yes        Yes             No        Yes        No       
Business Partner        Identifies a Business Partner                                                        Yes        Yes             No        Yes        No       
Business Partner Group  Business Partner Group                                                               Yes        Yes             No        Yes        No       
Partner Location        Identifies the (ship to) address for this Business Partner                           Yes        No              No        Yes        No       
Credit Status           Business Partner Credit Status                                                       Yes        Yes             No        Yes        No       
Company Agent           Company Agent                                                                        Yes        Yes             No        Yes        No       
Date Invoiced           Date printed on Invoice                                                              Yes        Yes             No        Yes        No       
Price List              Unique identifier of a Price List                                                    Yes        Yes             No        Yes        No       
Currency                The Currency for this record                                                         Yes        Yes             No        Yes        No       
Grand Total             Total amount of document                                                             Yes        Yes             No        Yes        No       
Document Status         The current status of the document                                                   Yes        Yes             No        Yes        No       
Paid                    The document is paid                                                                 Yes        Yes             No        Yes        No       
In Dispute              Document is in dispute                                                               Yes        Yes             No        No         No       
Description             Optional short description of the record                                             Yes        No              No        Yes        No       
Order                   Order                                                                                Yes        Yes             No        Yes        No       
Payment Rule            How you pay the invoice                                                              Yes        Yes             No        Yes        No       
Payment Term            The terms of Payment (timing, discount)                                              Yes        Yes             No        Yes        No       
Dunning Grace Date                                                                                           Yes        Yes             No        No         No       
Collection Status       Invoice Collection Status                                                            Yes        Yes             No        No         No       
Tax ID                  Tax Identification                                                                   Yes        Yes             No        Yes        No       
Tax Group                                                                                                    Yes        No              No        Yes        No       
Open Balance            Total Open Balance Amount in primary Accounting Currency                             Yes        No              No        Yes        No       
Credit Limit            Total outstanding invoice amounts allowed                                            Yes        No              No        Yes        No       
Credit Used             Current open balance                                                                 Yes        No              No        Yes        No       
Trx Organization        Performing or initiating organization                                                Yes        Yes             No        Yes        No       
Activity                Business Activity                                                                    Yes        Yes             No        Yes        No       
Campaign                Marketing Campaign                                                                   Yes        Yes             No        Yes        No       
Project                 Financial Project                                                                    Yes        No              No        Yes        No       
Account Date            Accounting Date                                                                      Yes        Yes             No        Yes        No       
Approved                Indicates if this document requires approval                                         Yes        No              No        Yes        No       
Posted                  Posting status                                                                       Yes        Yes             No        Yes        No       
======================  ===================================================================================  =========  ==============  ========  =========  =========
