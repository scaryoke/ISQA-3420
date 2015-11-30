# DFD Dictionary

# Entities

**Corporate Developer**- The user that will be contributing opensource code to the system.  

**Corporate Project Auditor**- User who oversees the project.  This is the user that will be oversees policy risk and vulnerability information. 

# Databases

**National Vulnerability Database**- Collection of known vulnerabilities.

**SPDX DB**- Collection of files in SPDX format. 

**Policy Database**- Collection of company polices. 

**NIST CPE Information**- XML file containing names of CPE names

**Online Repository** - Repository where license obligations are fulfilled.

# Processes

**Manage Code Information**- This is the process that interracts with the other processes that manage the risk/license information

**License Scanner**- This process scans the source code and returns the licence information with software.

**Manage CPE Information (Daily Job)** - This process checks daily for the updated CPE XML

**Manage CVE Information** - This process will check against the National Vulnerability Database for the vulnerability score.

**Manage Project Information** - This process will interract with all other processes that allow the project auditor to view risk information.

**Version Control/Build System** - This process is our build and version control of our software.

**Generate SHA-1** - This process generates the SHA-1 for a file/package sent in.

**Update Project Information** - This process allows the project auditor to update the environment where the code is deployed.

**Fulfill License**- This process fulfills the license obligation set by the code used in production.

# Data Flows

**File**- Source File
  
**Package**- Source Package comprised of one or more files

**License Info**- Each individual license that is associated with software

**Package Query**- A particular package that is being queried on

**CPE Information**- CPE name that will allow us to get the vulnerablity score

**CPE Request**- This contains the name of the software we are looking up

**CPE Response**- This will either return the CPE name or an empty string if no name is found

**CVE Response**- This will return the vulnerability score if one exists

**FILE SHA1 Request**- This will contain a generated SHA1.

**FILE SHA1 Response**- A yes/no response as to whether or not the hash of a file exists in the database. 

**License and Vulnerability information**- This will contain the licenses and vulnerability information associationd with a project.

**Policy Information Request**- Contains all of the license and vulnerability information associated with a project.

**Policy Information Response**- Returns all of of the policy information

**Project Info Request**- The name of the project

**Project Info Response**- This returns all of the project information

**Project Model Response**- This returns all of the code files used within a project

**Policy Approval**- A yes/no response to indicate if a project can continue

**Software Name**- The name of the software 

**Project Information**- Contains all of the licenses that a project is using.

**Project Environment**- Indicator of where the production environment is

**Community Notification**- Notification sent to the developer when a license needs to be fulfilled.
