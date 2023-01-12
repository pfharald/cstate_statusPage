---
title: Problem affecting some Papirfly web sites
date: 2022-11-14 05:30:00
resolved: true
resolvedWhen: 2022-11-14 09:30:00
# Possible severity levels: down, disrupted, notice
severity: down
affected:
  - Papirfly Web Services
section: issue
---

## Summary of the problems affecting access to some Papirfly Web Sites

The issues were caused by inaccessible databases and processing services in one of our production environments after a scheduled update.

05:15: Our systems were updated automatically (during a scheduled maintenance window) which caused some databases and processing services to be inaccessible

06:30: Problems with access to some Papirfly Web sites were detected by the first System Administrator arriving at the office

07:00: The issue causing inaccessible databases were identified and a fix applied

08:05: The issue causing problems with processing services were identified and a fix applied

08:10: Systems operational with degraded performance due to the processing backlog

09:30: Performance issues resolved and all systems operational


---
*Investigating* - We are experiencing problems with our database servers in one of our production environments making some of our Papirfly websites inaccessible. {{< track "2022-11-14 06:52:00" >}}

*Identified* - We have identified the issue and a fix has been applied. {{< track "2022-11-14 07:04:00" >}}

*Investigating* - We have detected additional issues causing degraded performance and problems with uploading assets. {{< track "2022-11-14 07:55:00" >}}

*Identified* - Problems with the uploading of assets were found and a fix has been applied, these issues were caused by problems with our image and video processing services. {{< track "2022-11-14 08:11:00" >}}

*Monitoring* - There may still be some degraded performance due to these recent problems, but we are constantly monitoring to ensure we pick up any other issues that may arise. {{< track "2022-11-14 09:18:00" >}}

*Resolved* - All systems operational {{< track "2022-11-14 10:27:00" >}}
