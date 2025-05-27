# 🐞 Bug Report Summary

## 🧾 Student Details  
**Name**: Fatuma Abdi Ibrahim
**Cohort**:  feb 2025
**Date**:  27th may 2025
---

## ✅ Expected Behaviors  

1. the app should sucessfully add tasks
2.the app should not add task if empty
3. task should be added by clicking complete

---

## 🐛 Reported Bugs  

### 🐞 BUG-001  
**Title**: [Empty task can be added]  
**GitHub Link**: [https://github.com/Fatuma81/Week-1software-testing-/tree/main]  
**Requirement Affected**: [Input Validation]  
**Severity**: [Low]  
**Summary**:  
The app allows users to add empty or whitespace-only tasks, which results in blank list items being displayed.
this allows entry of meaningless and confusing data display thus causing reduced data quality and acessibility issues 
---

### 🐞 BUG-002  
**Title**: ["clear all" Case/Space Sensitivity]  
**GitHub Link**: [https://github.com/Fatuma81/Week-1software-testing-/tree/main]  
**Requirement Affected**: [flexbility and reliability]  
**Severity**: [medium]  
**Summary**:  
The "clear all" command only works if typed exactly as "clear all" (lowercase, no extra spaces). Variants like "CLEAR  ALL" or " clear all " do not work reliably. The system should recognize and process special commands (like clear all) regardless of casing or extra whitespace, to enhance usability and error tolerance.this confuses users and It feels like the app misbehaves or is broken.
---

## 💭 Reflection  

Answer briefly (1–2 paragraphs):
I used observation and manual testing interacting with the application through the browser to observe how it behaved in response to different inputs.Entered valid and invalid tasks (e.g., empty text, duplicate tasks).Used special commands like "clear all" in different cases and spacing.

Easy:
Identifying obvious visual bugs (e.g., empty tasks being added).
Testing basic functionality like adding and marking tasks complete.
Understanding how the existing JavaScript code was structured.

Difficult:
Noticing that the "clear all" command was evaluated after being added.
Verifying if the app meets user experience and accessibility expectations without formal requirements.

I feel a little confident now:
I can spot both functional and usability/accessibility bugs.
I can clearly explain what went wrong, which requirement was affected, and how it should be fixed.
I'm also comfortable writing bug summaries
