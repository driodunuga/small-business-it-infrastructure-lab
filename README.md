# Small Business IT Infrastructure Lab

Home lab simulating a small business IT environment: Active Directory, networking, and security.

## Labs

### [01 - Active Directory](01-active-directory)
Windows Server 2019 domain controller running AD DS, DNS, DHCP, and NAT. Users created in bulk with PowerShell, and a Windows 10 client joined to the domain.

### 02 - pfSense Network Segmentation (in progress)
pfSense firewall placed in front of the domain to split servers and clients into separate subnets, with rules limiting client traffic to what Active Directory needs.

## Environment

- VirtualBox on Windows 11
- Windows Server 2019 (Evaluation)
- Windows 10 Pro
- pfSense CE
