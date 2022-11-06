# CyberPatriot Script for Windows

This directory contains scripts for Windows.

## Scripts

1. [EzScript](https://github.com/xFaraday/EzScript)

- This script would disable RDP. Please make sure to copy-paste segments of the
  script, if RDP is needed.
- A fresh installation of Windows Server in Round 2 of 2022 obtains 21 points
  from running this script, without considering 5 points that are deducted for
  disabling RDP.

2. **Secure_Baseline_LGPO**

- Resource created by [@anishgoyal1108](https://www.github.com/anishgoyal1108),
  making it reliable. However, the security baseline is not as strict as
  [EzScript](https://github.com/xFaraday/EzScript), at the expense of not
  deducting points or results harmful results.
- This baseline does not elevate privileges. Hence, you must run the script
  `install.` `cmd` with administrator privileges by hand.
- LGPO stands for local group policy object.
- Running this script alone gives 8 points in Round 2 of 2022 in Windows Server.

3. **Alternative Secure Baseline LGPO**

- Resource created by [@anishgoyal1108](https://www.github.com/anishgoyal1108),
  making it reliable. He spent an entire day creating this baseline, and it
  proudly gives us 12 points in Round 2 of 2022 in Windows Server.
- This baseline is configurable and adjustable to different versions of Windows.
- Execute `Windows 10 Version 1809 and Windows Server 2019 Security Baseline\Local_Script\BaselineLocalInstall.ps1` to install the baseline.
