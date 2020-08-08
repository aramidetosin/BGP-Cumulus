# BGP-Cumulus - Enabling BGP Unnumbered

The BGP unnumbered standard, laid out in RFC 5549, no longer requires an IPv4 prefix to be advertised along with an IPv4 next hop. That means you can set up BGP peering among your Cumulus Linux switches and exchange IPv4 prefixes without having to configure an IPv4 address on each switch. In other words, the interfaces used by BGP are unnumbered, at least when it comes to IPv4.
