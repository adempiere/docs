
.. _functional-guide/process/ad_user_hashpassword:

===========================
Convert passwords to hashes
===========================

Convert existing plain text/encrypted user passwords to one way hash

Help
====
This process will overwrite existing user passwords with a salted SHA-512 hash of the password so that they cannot be recovered if your database is compromised.

(Note: If your password column is currently encrypted, the hash will also be encrypted.)
