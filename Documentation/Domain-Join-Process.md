# Domain Join Process

## Objective

The objective of this phase was to successfully join a Windows client device to the Active Directory domain to simulate enterprise workstation integration and centralized authentication.

---

## Environment Details

| Component | Configuration |
|---|---|
| Domain Controller | DC01 |
| Client Machine | CL01 |
| Domain Name | deeskie.local |
| Operating System | Windows 11 Enterprise |
| DNS Server | DC01 |

---

## Domain Join Process

1. Verified network connectivity between CL01 and DC01.
2. Confirmed CL01 was using DC01 as its primary DNS server.
3. Opened System Properties on CL01.
4. Selected "Change Settings" under Computer Name.
5. Chose the option to join a domain.
6. Entered the domain name:
   
```text
deeskie.local
```

7. Authenticated using domain administrator credentials.
8. Successfully joined CL01 to the domain.
9. Restarted the client machine.
10. Verified domain authentication after reboot.

---

## Validation

The domain join process was validated by confirming:

- CL01 appeared in Active Directory Users and Computers
- Domain users could authenticate successfully
- Group Policy communication functioned properly
- DNS resolution worked correctly
- Domain trust relationship was established

---

## Commands Used

```powershell
ipconfig /all
ping dc01
nslookup dc01
gpupdate /force
```

---

## Issues Encountered

### Example Issues

- Incorrect DNS configuration
- Time synchronization mismatch
- RPC server unavailable errors
- Domain controller unreachable
- Authentication failures

---

## Troubleshooting Performed

### DNS Verification

Confirmed CL01 was pointing to DC01 for DNS resolution.

### Connectivity Testing

Validated communication between the client and domain controller using:

```powershell
ping dc01
```

### Secure Channel Validation

Tested trust relationship functionality between the workstation and domain.

---

## Lessons Learned

This phase reinforced the importance of DNS configuration, network communication, and authentication services within enterprise domain environments.

The successful domain join process demonstrated how centralized identity management enables enterprise workstation administration and policy enforcement.

---

## Screenshots

Screenshots will be added as the project progresses.
