# Skill 01: IT-GRC Daily PRD Risk Evaluator

**Primary Users:** Second-Line Defense, IT GRC, Claude Admins  
**Purpose:** Daily automated audit of completed PRDs for ICT risks and compliance triggers.

## 1. Claude Project Configuration
* **Project Name:** `IT-GRC: Automated PRD Risk Triage`
* **Custom Instructions:** Paste the raw text from `system_prompt.md`.

## 2. Project Knowledge
Upload the following files (located in the `/assets/` directory) into the Claude Project:
* `EN.02.01 ICT Project Management.pdf`
* `IT-GRC_Calibration_Examples.pdf`

## 3. The Daily Trigger Protocol
Paste this trigger prompt into the project chat interface every morning:
> "Run the daily IT-GRC triage. Fetch all PRDs in the Confluence PRD Repository that have been updated or marked 'Completed' in the last 24 hours. Output the full audit report for each using the defined Output Schema."
