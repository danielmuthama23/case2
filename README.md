# Humaein Screening Round - AI Full Stack Developer Application

## Overview
This repository contains solutions for the two take-home case studies as part of the Humaein AI Full Stack Developer screening process.

### Case Study #2: Cross-Platform Action Agent Using LLM + Browser Automation
- **File**: `case_study_2/email_action_agent.py`
- **Description**: An agent to send emails across Gmail and Outlook using Selenium and a mock LLM.
- **Run**: `python case_study_2/email_action_agent.py "Send an email to alice@example.com about the meeting at 2pm" --provider gmail`
- **API**: `uvicorn case_study_2/api/app:app --reload`

### Dependencies
Install with:
```bash
pip install -r requirements.txt# case2
