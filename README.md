This plugin allows users of AutonomIQ to trigger execution of suites via Jenkins

# Configuration:

Login to your Jenkins account > Click on Manage Jenkins > Click on Manage Plugins > Click on Advanced tab > Upload AutonomIQ’s hpi file to upload Plugin button > Click on upload.

# Usage:

Navigate to Jenkins project, either an existing project or a newly created one. 
Click on configure > Click on Add build step under Build section, 
Choose AutonomIQ plugin from the dropdown list and follow these steps:


1.	Provide AutonomIQ instance URL, username and password.
2.	Choose required project in the AutonomIQ user account from dropdown list.
3.	Click on Run test suites checkbox
4.	Choose available platform and browser combination.
5.	Enter list of suite names to run (one per line).
6.	Click on save
7.	Once user clicks on build now, suite execution will begin in AutonomIQ.

Note: (In case user needs to add multiple branches and and execute suites from different project. Click on Add build step again to add multiple branches and follow steps from (1-6)).

# View execution status:

Once the execution is completed, in order to view the status of execution.
Click on corresponding build > Click on console output.





