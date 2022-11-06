# Applies a Windows security configuration baseline to local group policy.

## Execute the script with one of these required command-line switches to install the corresponding baseline:

-Win10DomainJoined      - Windows 10 v1809, domain-joined
-Win10NonDomainJoined   - Windows 10 v1809, non-domain-joined
-WS2019Member           - Windows Server 2019, domain-joined member server
-WS2019NonDomainJoined  - Windows Server 2019, non-domain-joined
-WS2019DomainController - Windows Server 2019, domain controller

## EXAMPLE: BaselineLocalInstall.ps1 -Win10NonDomainJoined
