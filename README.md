# ConfigSources
LogicMonitor ConfigSources

**Active Directory ConfigSource Suite - Installation Guide**

Step 1: Import PropertySource from repository (if not a new account): addCategory_MicrosoftDomainController.

Step 2: Import ConfigSources - which use the hasCategory("MicrosoftDomainController") AppliesTo.

Troubleshooting:

Powershell remoting is used. You almost certainly need a domain admin credential for the collector account to query AD for this information (not fully tested.)


Active Directory Configs:

Admin Groups: list all members of Administrators, Domain Admins, Enterprise Admins, Schema Admins

Computers: list all Active Directory-joined computers

Domain Controllers: list all domain controllers in the domain

Domains: list all domains and properties

Forests: list all forests and properties

Group Policies: list all group policy objects

Groups: list all Groups in Active Directory

Organizational Units: list all organization units in Active Directory 

Password Policy: captures the default domain password policy and alerts when settings do not match Microsoft best practice.

Sites and Subnets: list all Active Directory Sites and Subnets

Users: list all Active Directory users
