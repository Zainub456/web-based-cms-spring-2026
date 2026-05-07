---
title: API overview and authentication
status: draft
audience: Development team
tags: [design, development]
---

Authentication required: Yes. Bearer token.
**Authorization:** 
Bearer <token>


Endpoint: Enable dark, light or system mode, and save setting
Create slider button (boolean) or true/false that gives notification of user selection. 

End user can change profile theme to light, dark or system, and save to profile. 


**Successful update: 200**
```json
{
  "status": "Your profile is updated",
  
}
```
Success message: "Theme updated" on push notification if saved correctly. 


**Error/unscucessful update: 401**
```json
{
  "status": "Invalid theme",
  
}
```
Error message: "Invalid theme" if spelled incorrectly. 


