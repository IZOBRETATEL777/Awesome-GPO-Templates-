# Make Windows Server 2022 CIS Compliant again!

The idae is to combine all ADMX/ADML files required for CIS Benchmark. Testted with version 2.0.0.

## Installation
Just make a directory called `PolicyDefinitions` in `\\<AD Domain>\SYSVOL\<AD Domain>\Policies` and put the content of the repository inside it.

![image](https://github.com/user-attachments/assets/9e5edf01-ae57-4b89-b8df-e2d01f7b0ea7)

Check, that Central store is used by the Group Policy Management tool (on DC).

![image](https://github.com/user-attachments/assets/f67605c1-7951-45b3-b3e3-a72a48c62e4c)

## Content

- Standard Windows 2022 Administrative Templates - coming out of the box

- Administrative Templates for Windows 11 September 2022 Update - [Official MS Downloads Portal](https://www.microsoft.com/en-us/download/details.aspx?id=104593)

- PerfTrack Policy Template - [from Harvester57](https://github.com/Harvester57/W10-ADMX/blob/master/PerformancePerftrack.admx)

- MSS Legacy Templates - [from nsacyber](https://github.com/nsacyber/Windows-Secure-Host-Baseline/blob/master/Windows/Group%20Policy%20Templates/MSS-legacy.admx)

## Disclaimer
At your own risk.
