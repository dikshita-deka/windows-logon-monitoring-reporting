# windows-logon-monitoring-reporting

Windows security lab covering logon monitoring, process auditing, PowerShell, and HTML reporting.

## Project Overview

This course project focuses on enhancing Windows security by monitoring failed and successful logon activities, recording process creation events, and generating security reports.

## Objectives

* Configure auditing for failed logon attempts.
* Enable process creation auditing and command-line logging.
* Track successful logon activity.
* Generate an HTML report of failed logon attempts using PowerShell.

## Tools Used

* Windows 11 Pro
* Oracle VirtualBox
* Event Viewer
* Local Security Policy
* Local Group Policy Editor
* PowerShell
* Command Prompt
* Microsoft Edge
* HTML

## Tasks Completed

### Task 1: Logon Failure Analysis

Configured auditing for failed logon attempts and verified the events in Windows Event Viewer.

**Event ID:** 4625

### Task 2: Command Logging Configuration

Enabled process creation auditing and command-line logging, then verified the recorded events.

**Event ID:** 4688

### Task 3: Successful Logon Tracking

Configured successful logon auditing and created a PowerShell script to retrieve recent successful logon events.

**Event ID:** 4624
**Script:** SuccessfulLogonTracker.ps1

### Task 4: Web-Based Reporting

Created a PowerShell script to retrieve recent failed logon events and generate an HTML report, which was opened in Microsoft Edge.

**Script:** FailedLogonReport.ps1

## Project Files

* **Project Write-up:** Detailed documentation of the tasks performed.
* **FailedLogonReport.ps1:** PowerShell script for generating an HTML report of failed logon attempts.
* **SuccessfulLogonTracker.ps1:** PowerShell script for retrieving successful logon events.
* **Screenshots:** Evidence of configurations, event logs, PowerShell results, and HTML reporting.

## Key Learnings

* Windows security auditing and log monitoring.
* Analysis of failed and successful logon events.
* Process creation and command-line auditing.
* Retrieving Windows Security events using PowerShell.
* Generating HTML reports for security monitoring.

## Project Context

This is a course-based cybersecurity lab project documenting the implementation tasks, tools used, and results observed.
