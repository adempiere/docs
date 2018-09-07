
.. _functional-guide/process/sbp_paymentgeneratefrominvoice:

========================================
Payment Generate (From Invoice Customer)
========================================

Generate Payment from selected invoices

Parameters
==========

Currency
--------
\ **Description**\ 
 \ *The Currency for this record*\ 
\ **Help**\ 
 \ *Indicates the Currency to be used when processing or reporting on this record*\ 

.. note::
    null

Target Document Type
--------------------
\ **Description**\ 
 \ *Target document type for conversing documents*\ 
\ **Help**\ 
 \ *You can convert document types (e.g. from Offer to Order or Invoice).  The conversion is then reflected in the current type.  This processing is initiated by selecting the appropriate Document Action.*\ 

Document Date
-------------
\ **Description**\ 
 \ *Date of the Document*\ 
\ **Help**\ 
 \ *The Document Date indicates the date the document was generated.  It may or may not be the same as the accounting date.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Bank Account
------------
\ **Description**\ 
 \ *Account at the Bank*\ 
\ **Help**\ 
 \ *The Bank Account identifies an account at this Bank.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Payment date
------------
\ **Description**\ 
 \ *Date Payment made*\ 
\ **Help**\ 
 \ *The Payment Date indicates the date the payment was made.*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Tender type
-----------
\ **Description**\ 
 \ *Method of Payment*\ 
\ **Help**\ 
 \ *The Tender Type indicates the method of payment (ACH or Direct Deposit, Credit Card, Check, Direct Debit)*\ 

.. note::
    The field must have a value for the record to be saved to the database.

Payment amount
--------------
\ **Description**\ 
 \ *Amount being paid*\ 
\ **Help**\ 
 \ *Indicates the amount this payment is for.  The payment amount can be for single or multiple invoices or a partial payment for an invoice.*\ 

Over/Under Payment
------------------
\ **Description**\ 
 \ *Over-Payment (unallocated) or Under-Payment (partial payment)*\ 
\ **Help**\ 
 \ *Overpayments (negative) are unallocated amounts and allow you to receive money for more than the particular invoice. 
Underpayments (positive) is a partial payment for the invoice. You do not write off the unpaid amount.*\ 

Routing No
----------
\ **Description**\ 
 \ *Bank Routing Number*\ 
\ **Help**\ 
 \ *The Bank Routing Number (ABA Number) identifies a legal Bank.  It is used in routing checks and electronic transactions.*\ 

Account No
----------
\ **Description**\ 
 \ *Account Number*\ 
\ **Help**\ 
 \ *The Account Number indicates the Number assigned to this bank account.*\ 

Check No
--------
\ **Description**\ 
 \ *Check Number*\ 
\ **Help**\ 
 \ *The Check Number indicates the number on the check.*\ 

Micr
----
\ **Description**\ 
 \ *Combination of routing no, account and check no*\ 
\ **Help**\ 
 \ *The Micr number is the combination of the bank routing number, account number and check number*\ 

Credit Card
-----------
\ **Description**\ 
 \ *Credit Card (Visa, MC, AmEx)*\ 
\ **Help**\ 
 \ *The Credit Card drop down list box is used for selecting the type of Credit Card presented for payment.*\ 

Transaction Type
----------------
\ **Description**\ 
 \ *Type of credit card transaction*\ 
\ **Help**\ 
 \ *The Transaction Type indicates the type of transaction to be submitted to the Credit Card Company.*\ 

Number
------
\ **Description**\ 
 \ *Credit Card Number*\ 
\ **Help**\ 
 \ *The Credit Card number indicates the number on the credit card, without blanks or spaces.*\ 

Verification Code
-----------------
\ **Description**\ 
 \ *Credit Card Verification code on credit card*\ 
\ **Help**\ 
 \ *The Credit Card Verification indicates the verification code on the credit card (AMEX 4 digits on front; MC,Visa 3 digits back)*\ 

Exp. Month
----------
\ **Description**\ 
 \ *Expiry Month*\ 
\ **Help**\ 
 \ *The Expiry Month indicates the expiry month for this credit card.*\ 

Exp. Year
---------
\ **Description**\ 
 \ *Expiry Year*\ 
\ **Help**\ 
 \ *The Expiry Year indicates the expiry year for this credit card.*\ 

Account Name
------------
\ **Description**\ 
 \ *Name on Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Name of the Credit Card or Account holder.*\ 

Account Street
--------------
\ **Description**\ 
 \ *Street address of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The Street Address of the Credit Card or Account holder.*\ 

Account City
------------
\ **Description**\ 
 \ *City or the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Account City indicates the City of the Credit Card or Account holder*\ 

Account Zip/Postal
------------------
\ **Description**\ 
 \ *Zip Code of the Credit Card or Account Holder*\ 
\ **Help**\ 
 \ *The Zip Code of the Credit Card or Account Holder.*\ 

Account State
-------------
\ **Description**\ 
 \ *State of the Credit Card or Account holder*\ 
\ **Help**\ 
 \ *The State of the Credit Card or Account holder*\ 

Account Country
---------------
\ **Description**\ 
 \ *Country*\ 
\ **Help**\ 
 \ *Account Country Name*\ 

Driver License
--------------
\ **Description**\ 
 \ *Payment Identification - Driver License*\ 
\ **Help**\ 
 \ *The Driver's License being used as identification.*\ 

Social Security No
------------------
\ **Description**\ 
 \ *Payment Identification - Social Security No*\ 
\ **Help**\ 
 \ *The Social Security number being used as identification.*\ 

Account EMail
-------------
\ **Description**\ 
 \ *Email Address*\ 
\ **Help**\ 
 \ *The EMail Address indicates the EMail address off the Credit Card or Account holder.*\ 

Tax Amount
----------
\ **Description**\ 
 \ *Tax Amount for a document*\ 
\ **Help**\ 
 \ *The Tax Amount displays the total tax amount for a document.*\ 

PO Number
---------
\ **Description**\ 
 \ *Purchase Order Number*\ 
\ **Help**\ 
 \ *The PO Number indicates the number assigned to a purchase order*\ 

Voice authorization code
------------------------
\ **Description**\ 
 \ *Voice Authorization Code from credit card company*\ 
\ **Help**\ 
 \ *The Voice Authorization Code indicates the code received from the Credit Card Company.*\ 

Original Transaction ID
-----------------------
\ **Description**\ 
 \ *Original Transaction ID*\ 
\ **Help**\ 
 \ *The Original Transaction ID is used for reversing transactions and indicates the transaction that has been reversed.*\ 
