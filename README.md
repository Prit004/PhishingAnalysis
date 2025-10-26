This repository contains my phishing email analysis submission.


Contents
- report.pdf : Full analysis with remediation steps
- sample_email.eml : Original email (sanitized)
- header_analysis.txt : SPF/DKIM/DMARC and Received-line analysis
- screenshots/ : Hover link and header analysis screenshots
- artifacts/ : Any attachments examined
- checklist.txt : Task completion checklist


Summary
The email analyzed was classified as phishing due to:
- Failing SPF/DKIM/DMARC checks
- Suspicious links with mismatched visible text
- Urgent threatening language