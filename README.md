A fork of nfdump(http://nfdump.sourceforge.net)

Add some features

1. nfdump 'filter expression' support '[dir] in [ifindex1,ifindex2...]'
example:
   nfdump -r nffile "in if in [19,20,21]"

2. nfcapd support specific sampling rate for each router
example:
   nfcapd -r 10.10.10.10/1000,10.10.10.11/2000


