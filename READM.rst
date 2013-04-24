==============================
A fork of nfdump(http://nfdump.sourceforge.net)
==============================

Add some features:
--------

 - snmp interface list filter.  
     usage :  [dir] if in [<iflist>]' 
  example:
     in if in [1,2,3,4]

 - nfcapd support specific sampling rate for each router example
  example:
     nfcapd -r 10.10.10.10/1000,10.10.10.11/2000

 - service name filter.
     usage : service [servciename]

  example:
     nfdump -r nf.nfcapd "servcie http or service udp"
