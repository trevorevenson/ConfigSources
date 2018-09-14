# ConfigSources

**ConfigSource Suites - Installation Guide**

Step 1: Make sure your PropertySources are up to date by importing from repository.

Step 2: Import ConfigSources - either individually or grouped (as outlined in the next section.)

**Combined Configs:**

Multiple configs within a suite are now available within the "Merged" folder - single file import is convenient!

**Active Directory Configs:**

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

**Troubleshooting**:

Powershell remoting is used. You almost certainly need a domain admin credential for the collector account to query AD for this information (not fully tested.)
