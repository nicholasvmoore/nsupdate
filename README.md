nsupdate
========
(c) 2014 Karl J. Vesterling

PURPOSE:
--------
Maintaining Current DNS:
This script will go out and update A records to point to the new
ip address.  It's a LOT like dyndns.org, however you can in fact
create/remove/update any number of things, such as SRV records, or
TXT records.

Automatic IP6-in-IP4 Tunnel Endpoint configuration:
The script currently uses wget in order to update the ip6-in-ip4
tunnel endpoint to reflect the new internet addressable IP4 address
we were assigned.

Restart Communications:
Some things need to be restarted in order for them to operate correcty.
the script has a section where you can add/remove start/stop service
statements.  This will probably be further refined by me such that a
configuration file may be used instead.
What it does currently is 
