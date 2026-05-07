---
title: API overview and authentication
status: draft
audience: Development team
tags: [design, development]
---

Authentication required: Yes. Bearer token.
**Authorization:** 
Bearer <token>


**Endpoint:**
End user can change profile theme to high contrast or dark mode and save to profile. 

<ul>High contrast setting: Increase contrast for better readability. </ul>
<ul>Dark mode setting: Set theme to a dark color, like black or grey. </ul>
<ul>System: Defaut setting  </ul>

<br>

**Request**
Create slider button (boolean) or true/false that gives notification of user selection. 




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




