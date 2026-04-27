---
title: API overview and authentication
status: draft
audience: Development team
tags: [design, development]
---


Endpoint: Enable dark, light or system mode, and save settings

End user can change profile theme to light, dark or system, and save to profile. 

Create slider button (boolean) that gives notification of user selection. 

Authentication required: Yes. Bearer token. 

Error message: "Invalid theme" if spelled incorrectly. 

Success message: "Theme updated" on push notification if saved correctly. 