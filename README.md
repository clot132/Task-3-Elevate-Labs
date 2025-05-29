# Task-3-Elevate-Labs

Task 3: Perform a Basic Vulnerability Scan on Your PC
 Objective:
Use free tools to identify common vulnerabilities on your computer.

🛠 Tools:

OpenVAS (Greenbone Vulnerability Manager) Community Edition
(Alternative: Nessus Essentials)

 Deliverables:

Vulnerability scan report with identified issues

Screenshots of scan results

Documentation of critical findings and fixes

Steps to Perform the Scan (Using OpenVAS)
Install OpenVAS (GVM)
Run these commands:

1.
sudo apt update
sudo apt install openvas
sudo gvm-setup
Start GVM Services

2.
sudo gvm-check-setup
sudo gvm-start
Access the Web Interface
Open your browser and go to:
https://localhost:9392
Use the admin credentials generated during gvm-setup.
Screenshot Attached Img1.

3. By clicking on the link in Img1. The following interface opens(see Img2).
4. Set Up a New Target

Go to Configuration > Targets

Click New Target


Create a New Task (Scan Job)

Go to Scans > Tasks > New Task

Set:

Name: Localhost Vulnerability Scan

Target: the one you just created

Scan Config: Full and fast

Start the Scan

Click the scan task name

Click the Start Scan button

Wait for Scan Completion

It may take 30–60 minutes

Status will change to Done once complete

Review the Report

5. Go to Scans > Reports

Click your scan result

Review vulnerabilities listed by severity (High, Medium, Low)

Research Fixes

6. For each critical CVE found, search for:

Patch or upgrade commands

Configurations to mitigate

Official advisories or security bulletins
7. Scan File Attached see OpenVas Scan report.pdf
