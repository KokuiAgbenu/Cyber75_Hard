# Day 03 Lab: Setting up mock vulnerability management program

# **Date:** 28-10-2025

## Objective

Learning about vulnerability management policies, CAB (change advisory board), and creating an insecure server for the purposes of scanning.

## Steps Completed

1. Created windows server 2019 using Azure.
2. Introduced vulnerabilities 
3. Created and ran an authenticated scan in Tenable of the server
4. Reviewed scan results to observe vulnerabilities.

## Key Learnings

* Creating a vulnerability management policy requires meetings with all teams that could be affected by the policy or any scans that take place due to the policy. These meetings may result in amendments to the draft policy documents being made. 
* Once all teams agree, the policy document is signed off by upper management. 
* Though you have the policy document signed it's still good practice to get authorisation from the head of each team to scan their systems. Also gives you a chance to get any credentials you need. 

## Notes / Observations

* Multiple steps and meetings to getting a vulnerability management program started. 
* Command to force restart of machine in PowerShell > *shutdown /r /t 0 /f*
* Clear command line using *cls*

## Next Steps

* Asses vulnerabilities and prioritise remediation.
