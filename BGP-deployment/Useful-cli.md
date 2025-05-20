## Useful commands for Cisco CLI

### Routing

- `show ip route`: Displays the routing table.
- `show ip route <network>`: Displays the routing table for a specific network.

- `show bgp ipv6 unicast` : Displays the BGP routing table for IPv6 unicast.
- `show ip bgp summary`: Displays a summary of BGP neighbors and their status.
- `show ip bgp neighbors`: Displays detailed information about BGP neighbors.
- `show ip bgp <network>`: Displays BGP information for a specific network.

### BGP

- `clear ip bgp <neighbor>`: Clears the BGP session with a specific neighbor.
- `clear ip bgp <neighbor> out`: Clears the BGP session with a specific neighbor and applies the inbound policy.
- `clear ip bgp <neighbor> in`: Clears the BGP session with a specific neighbor and applies the outbound policy.

- `clear bgp ipv6 unicast <neighbor>`: Clears the BGP session with a specific IPv6 neighbor.
- `clear bgp ipv6 unicast <neighbor> out`: Clears the BGP session with a specific IPv6 unicast neighbor.
- `clear bgp ipv6 unicast <neighbor> in`: Clears the BGP session with a specific IPv6 unicast neighbor and applies the outbound policy.

- `clear bgp all <asn>`: Clears all BGP sessions for a specific ASN.

- `show ip bgp community`: Displays BGP information for a specific network.

### Mics / Linux

- `whois <ip>` : Displays information about the IP address, including the owner and location.
- `whois <domain>` : Displays information about the domain, including the owner and location.
- `whois –h whois.arin.net x.x.x.0/24` : Queries the ARIN database for information about the IP address range.
