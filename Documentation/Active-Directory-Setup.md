# Active Directory Setup

## Objective

The objective of this lab phase was to deploy and configure Active Directory Domain Services to simulate an enterprise identity management environment.

## Environment Details

| Component | Configuration |
|---|---|
| Domain Controller | DC01 |
| Domain Name | deeskie.local |
| Client Machine | CL01 |
| Server Role | Active Directory Domain Services / DNS |
| Environment Type | Enterprise Infrastructure Lab |

## Implementation Steps

1. Installed Windows Server.
2. Renamed the server to DC01.
3. Assigned a static IP address.
4. Installed the Active Directory Domain Services role.
5. Promoted DC01 to a domain controller.
6. Created the deeskie.local domain.
7. Verified DNS configuration.
8. Joined a Windows client device to the domain.

## Validation

The Active Directory environment was validated by confirming:

- DC01 was promoted successfully.
- DNS zones were created.
- Domain user accounts could be created.
- CL01 was able to join the domain.
- Domain authentication worked successfully.

## Issues Encountered

Document any issues here, such as:

- DNS misconfiguration
- Time synchronization problems
- Domain join errors
- Authentication failures

## Lessons Learned

This phase helped reinforce the importance of DNS, static IP addressing, domain controller configuration, and proper validation when deploying enterprise identity infrastructure.

## Screenshots

Screenshots will be added as the lab progresses.

[View Screenshots Folder](./Screenshots/)
