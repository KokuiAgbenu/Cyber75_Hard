# Day 01 Lab: Programmatic Remediation in Windows 

# **Date:** 26-10-2025

## Objective

Using PowerShell to programmatically remediate Firefox, SMB1, TLS vulnerabilities on a Windows 10 machine.

## Steps Completed

1. Created Win 10 virtual machine.
2. Introduced vulnerabilities - outdated Mozilla Firefox browser, enabled SMB1 protocol, and enabled TLS protocol.
3. Ran authenticated Tenable scan.
4. Observed vulnerabilities from Tenable scan report.
5. Ran PowerShell scripts to remediate the vulnerabilities.
6. Ran 2nd authenticated scan to verify remediation.

## Key Learnings

* When doing authenticated scans in Tenable, double check the credentials are entered correctly. Inputting credentials incorrectly wastes time having to re-run scans. 

## Notes / Observations

* The PowerShell script to remediate SMB1 is essentially a series of registry key changes.

## Next Steps

* Repeat this lab for a Linux machine.
