# CyberPatriot script for All Platform

All those scripts in this directory may run for Windows & Linux. Optionally, it might support a cisco router.

## Scripts

1. [BaiqingL's CyberPatriot Scripts (2016)](https://github.com/BaiqingL/CyberPatriotScripts)

- Linux
  - Notice this script is manually replacing configuration files of
  `sources.list`, `lightdm.conf`, `sshd_confg` and similar files. with their
  reference file. Those files are 6 years old and result in a lot of errors.
    - Package repo is broken
    - `sshd` complains about deprecated configuration
  - This script just calls common commands and asks you to determine if
  anything went wrong.
  - It does not like `ufw`, it just calls `iptables` to set up firewall. There is
    a lot of hard-coded addresses and ports.
  - Installs all kinds of anti-virus software.
- Windows
  - Not tested.
