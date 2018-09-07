
.. _functional-guide/smart-browse/transportlicensebrowser:

=========================
Transport License Browser
=========================


.. seealso::
    :ref:`functional-guidewindow-transportlicense`


.. seealso::
    :ref:`functional-guideprocess-dd_transportlicenseselection`


.. note::
    The Records Deletable checkbox indicates if a record can be deleted from the database.  If records cannot be deleted, you can only deselect the Active flag
Allows auto select rows of a browser
Allow define if a Browser is execute by default

Fields
======


======================  =================================================================  =========  ==============  ========  =========  =========
Name                    Description                                                        Displayed  Query Criteria  Order By  Read Only  Mandatory
======================  =================================================================  =========  ==============  ========  =========  =========
License                                                                                    Yes        No              No        Yes        No       
Transport License Type                                                                     No         Yes             No        Yes        No       
License Type                                                                               No         Yes             No        Yes        No       
Organization            Organizational entity within client                                Yes        No              No        Yes        No       
Search Key              Search key for the record in the format required - must be unique  Yes        Yes             No        Yes        No       
Name                    Alphanumeric identifier of the entity                              Yes        No              No        Yes        No       
Valid from              Valid from including this date (first day)                         Yes        Yes             No        No         No       
Valid to                Valid to including this date (last day)                            Yes        Yes             No        No         No       
Active                  The record is active in the system                                 Yes        Yes             No        No         No       
======================  =================================================================  =========  ==============  ========  =========  =========
