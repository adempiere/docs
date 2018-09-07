
.. _functional-guide/process/process-ad_changelog_custom:

======================
Reapply Customizations
======================

If you identified customizations in the Change Log, you can reapply them

Help
====
The migration "resets" the system to the current/original setting.  If selected in the Change Log, you can save the customization and re-apply them.  Please note that you need to check, if your customization has no negative side effect in the new release. 
Shut down the Application Server before running this process and set the Trace level (in Preference) higher or equals  WARNING.

Parameters
==========

Only Set Customization
----------------------
\ **Description**\ 
 \ *Set Customization for change records records with Dictionary Entity Type*\ 

Validate current (old) Value
----------------------------
\ **Description**\ 
 \ *Ensure that the old value of the change is the current value in the system (i.e. original situation)*\ 

.. note::
    The field must have a value for the record to be saved to the database.
