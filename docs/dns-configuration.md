# LinuxCat DNS Configuration

Domain: linuxcat.site

DNS provider currently documented:
Namecheap BasicDNS

## Nameservers

dns1.registrar-servers.com
dns2.registrar-servers.com

## DNS Records

| Record | Host | Purpose |
|--------|------|---------|
| A | @ | Root domain IPv4 |
| CNAME | www | Website alias |
| NS | @ | Authoritative nameserver |
| SOA | @ | Zone authority information |

## DNS Testing

```bash
dig linuxcat.site
dig linuxcat.site A
dig linuxcat.site NS
dig linuxcat.site MX
nslookup linuxcat.site
