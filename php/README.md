php
===

You have to create automation.ini and a password file to this script work for you, just copy .template files and edit them

Password file format:

`` <delimiter><tracker><delimiter><usermame><delimiter><password><delimiter>

Examples:

 |bibliotik|Notos|myPassw0rd|
 :what.cd:Notos:myPassw0rd:
 @btn@Notos@myPassw0rd@

You choose what delimiter to use, it can be different from line to line

Please secure your password file using "chmod 600" and run an instance of php under your user account
