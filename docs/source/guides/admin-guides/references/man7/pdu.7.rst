
#####
pdu.7
#####

.. highlight:: perl


****
NAME
****


\ **pdu**\  - a logical object definition in the xCAT database.


********
SYNOPSIS
********


\ **pdu Attributes:**\   \ *machinetype*\ , \ *modelnum*\ , \ *node*\ , \ *nodetype*\ , \ *outlet*\ , \ *serialnum*\ 


***********
DESCRIPTION
***********


Logical objects of this type are stored in the xCAT database in one or more tables.  Use the following commands
to manipulate the objects: \ **mkdef**\ , \ **chdef**\ , \ **lsdef**\ , and \ **rmdef**\ .  These commands will take care of
knowing which tables the object attributes should be stored in.  The attribute list below shows, in
parentheses, what tables each attribute is stored in.


***************
pdu Attributes:
***************



\ **machinetype**\  (pdu.machinetype)



\ **modelnum**\  (pdu.modelnum)



\ **node**\  (pdu.node)
 
 The hostname/address of the pdu to which the settings apply
 


\ **nodetype**\  (pdu.nodetype)
 
 The node type should be pdu
 


\ **outlet**\  (pdu.outlet)
 
 The pdu outlet count
 


\ **serialnum**\  (pdu.serialnum)




********
SEE ALSO
********


\ **mkdef(1)**\ , \ **chdef(1)**\ , \ **lsdef(1)**\ , \ **rmdef(1)**\ 

