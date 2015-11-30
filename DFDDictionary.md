# DFD Dictionary

# Entities

**Corporate Developer**- The user that will be contributing opensource code to the system.  

**Corporate Project Auditor**- User who oversees the project.  This is the user that will be oversees policy risk and vulnerability information. 

# Databases

**National Vulnerability Database**- Collection of known vulnerabilities.

**SPDX DB**- Collection of files in SPDX format. 

**Policy Database**- Collection of company polices. 

**NIST CPE Information**- New process builds zip.


# Processes

**Manage Code Information**- This is the process that interracts with the other processes that manage the risk/license information

**License Scanner**- This process scans the source code and returns the licence information with software.

**Manage CPE Information (Daily Job)** - This process checks daily for the updated CPE XML

**Manage CVE Information** - This process will check against the National Vulnerability Database for the vulnerability score.

**Manage Project Information** - This process will interract with all other processes that allow the project auditor to view risk information.

**Version Control/Build System** - This process is our build and version control of our software.

**Generate SHA-1** - This process generates the SHA-1 for a file/package sent in.

# Data Flows

**File**- Source File
  
**Package**- Source Package comprised of one or more files

**License Info**-

**Package Query**-

**CPE Information**-

**CPE Request**- 

**CPE Response**-

**CVE Request**-

**CVE Response**-

**FILE SHA1 Request**-

**FILE SHA1 Response**- A yes/no response as to whether or not the hash of a file exists in the database. 

**File license and CPE information**-

**File Information Request**-

**File Information Response**-

**Project Info Request**-

**Project Info Response**-

**Project Model Response**-

**Policy Approval**-

**Software Name**-

**Project Information**-

**External Entites**-

**Data Stores**-
