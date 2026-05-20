# DNS Configuration

## Objective

The objective of this phase was to configure Domain Name System (DNS) services to support Active Directory functionality and enterprise name resolution.

---

## Environment Details

| Component | Configuration |
|---|---|
| DNS Server | DC01 |
| Domain | deeskie.local |
| DNS Role | Active Directory Integrated DNS |
| Network Range | 10.10.0.0/20 |

---

## DNS Configuration Steps

1. Installed the DNS Server role during Active Directory deployment.
2. Verified Forward Lookup Zones were created automatically.
3. Confirmed deeskie.local zone functionality.
4. Configured client devices to use DC01 as primary DNS server.
5. Tested DNS resolution using nslookup and ping.
6. Verified domain controller discoverability.

---

## Validation

DNS functionality was validated by confirming:

- Successful hostname resolution
- Domain controller discoverability
- Successful domain joins
- Proper forward lookup zone creation
- Reliable client authentication

---

## Commands Used

```powershell
ipconfig /all
nslookup dc01
ping dc01
```

---

## Issues Encountered

### Example Issues

- DNS server not resolving hostnames
- Incorrect client DNS settings
- Domain join failures due to DNS
- Missing Forward Lookup Zones

---

## Lessons Learned

This phase reinforced the critical role DNS plays within Active Directory environments. Proper DNS configuration is essential for authentication, domain discovery, policy application, and enterprise connectivity.

---

## Screenshots

Screenshots will be added as the lab progresses.
