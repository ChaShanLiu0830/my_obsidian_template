---
research name: <% tp.file.folder()%>
date: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - research
  - progress
  - machine
  - learning
  - keywords
---
<%*
const parentFolderName = tp.file.folder(true).split('/').slice(-2, -1)[0];
const todayDate = tp.date.now("YYYY-MM-DD");
await tp.file.rename(`${parentFolderName}`);
%>

# <%tp.file.folder()%> Progress - <% tp.file.title %>

---

**Date Created:** <% tp.date.now("YYYY-MM-DD") %>  
**Last Modified:** <% tp.date.now("YYYY-MM-DD") %>

---

## Summary
> Provide a brief summary of the current progress.

## Task List
### Ongoing Tasks
- [ ] Task 1: [Describe Task 1]
- [ ] Task 2: [Describe Task 2]

### Completed Tasks
- [x] Task 1: [Describe Completed Task 1] <% tp.date.now("YYYY-MM-DD") %>
- [x] Task 2: [Describe Completed Task 2] <% tp.date.now("YYYY-MM-DD") %>

## Detailed Progress
### <% tp.date.now("YYYY-MM-DD") %>
**Activities:**
- [Describe today's activities]

**Findings:**
- [Describe today's findings]

**Challenges:**
- [Describe today's challenges]

### <% tp.date.now("YYYY-MM-DD", "+1d") %>
**Activities:**
- [Describe the next day's activities]

**Findings:**
- [Describe the next day's findings]

**Challenges:**
- [Describe the next day's challenges]

## Next Steps
> Outline the next steps based on the current progress.

## Notes
> Include any additional notes or thoughts related to the research progress.

---

**Status:** [Enter status (e.g., In Progress, Completed)]  
**Review Date:** <% tp.date.now("YYYY-MM-DD", "+7d") %>  <!-- Review date set to one week from now -->