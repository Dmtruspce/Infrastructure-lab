# Group Policy Deployment

## Objective

The objective of this phase was to deploy and manage Group Policy Objects (GPOs) within the Active Directory environment to simulate centralized enterprise configuration management.

---

## Environment Details

| Component | Configuration |
|---|---|
| Domain Controller | DC01 |
| Domain | deeskie.local |
| Policy Management Tool | Group Policy Management Console |
| Client Machine | CL01 |

---

## Group Policy Deployment Process

1. Opened Group Policy Management Console (GPMC).
2. Created Organizational Units (OUs) for policy targeting.
3. Created a new Group Policy Object.
4. Linked the GPO to the appropriate Organizational Unit.
5. Configured policy settings.
6. Applied policy updates to client systems.
7. Verified policy application on CL01.

---

## Policies Configured

### Example Policies

- Password policy enforcement
- Desktop restrictions
- Windows Update configuration
- Remote Desktop settings
- Security hardening settings
- Control Panel restrictions

---

## Validation

The Group Policy deployment was validated by confirming:

- GPO linkage status
- Successful policy inheritance
- Policy application on client devices
- gpupdate execution success
- Expected configuration enforcement

---

## Commands Used

```powershell
gpupdate /force
gpresult /r
rsop.msc
```

---

## Organizational Structure

### Example OU Structure

```text
deeskie.local
│
├── Workstations
├── Servers
├── Users
└── Admin Accounts
```

---

## Issues Encountered

### Example Issues

- GPO not applying
- Replication delays
- Incorrect OU placement
- Security filtering issues
- DNS communication problems

---

## Troubleshooting Performed

### Policy Refresh

Forced policy updates using:

```powershell
gpupdate /force
```

### Resultant Set of Policy Verification

Validated applied policies using:

```powershell
rsop.msc
```

### Group Policy Results

Reviewed applied and denied policies using:

```powershell
gpresult /r
```

---

## Lessons Learned

This phase reinforced the importance of centralized configuration management within enterprise environments.

Group Policy provides administrators with scalable control over user settings, device configurations, and security enforcement across the domain.

---

## Future Improvements

Planned future policy implementations include:

- BitLocker deployment
- Drive mapping automation
- Software deployment
- Advanced security hardening
- PowerShell execution policies
- Windows Defender management

---

## Screenshots

![Group Policy Tree](../Screenshots/Group-policy-Tree1.png)
