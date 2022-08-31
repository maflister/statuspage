---
title: Open OnDemand File Upload Issue
date: 2022-02-25 12:00:00
informational: true
resolved: true
resolvedWhen: 2022-08-03 21:00:00
# Possible severity levels: down, disrupted, notice
severity: notice
affected:
  - Open OnDemand
section: issue
---

*Resolved* -
RCC updated Open OnDemand during monthly maintenance.

*Monitoring* - RCC has identified a known issue with the Files App Upload feature. The issue causes large file uploads (>2Gb) to report failures. The file is still uploaded successfully, even if you see a failure. Please note that you may need to wait for some time to see the uploaded file appear in your storage. To avoid this issue, please consider using an alternative SFTP solution to upload files.
