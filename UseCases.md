Use Case #1

Title: Determine License and Vulnerability Information 

Primary Actor: Corporate Manager

Goal in Context: The corporate manager is able to determine license and vulnerability information from provided project information

Stakeholders: 

Corporate Project Auditor: To receive clear and relevant project information

Corporate Developer: To provide the relevant file/package level information 

Project Owner: To clearly understand corporate manager decisions to green/red light a project 

Preconditions:  Relevant and accurate file/package information is in the SPDX database
                Proper project information has been provided  

Main Success Scenario: Corporate manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions: Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages

Trigger: Corporate manager uploads or identifies project information to which license and vulnerability information is provided


Use Case #2

Title: Developer commits project

Primary Actor: Developer

Goal in Context: The developer is able to add code to projects. 

Stakeholders: Corporate Managers, Developers

Corporate Project Auditor: To determine if the commits adhere to the corporations policies.

Corporate Developer: To add code to projects that is clear, concise, and follows corporate policies.   

Project Owner: Developers

Preconditions: System is current and functional at time of commit.  

Main Sucess Scenario: Developer's code is accurate and inline with corporate policies.  All vulnerabilites and licenses have been addressed per policy procedure.

Failed End Conditions: Licenses and/or vulnerabilities are not in line with corporate policy.  Code is not accurate. 

Trigger: Developer completes code and is ready to commit. 
