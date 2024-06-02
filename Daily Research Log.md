
<%*
const parentFolderName = tp.file.folder(true).split('/').slice(-2, -1)[0];
const todayDate = tp.date.now("YYYY-MM-DD");
await tp.file.rename(`${todayDate} - Daily Research Log`);
%>

---
title: "<% tp.date.now("YYYY-MM-DD") %> - Daily Research Log"
date: <% tp.date.now("YYYY-MM-DD") %>
tags: [daily notes, research, <% parentFolderName %>  ]

---

# <% tp.date.now("YYYY-MM-DD") %> - Daily Research Log

**Date:** <% tp.date.now("YYYY-MM-DD") %>  
**Research Topic:** <% parentFolderName %>  
**Status:** [In Progress / Completed]

---

## Morning Planning
- **Objectives**: [Objective 1], [Objective 2]
- **Tasks**: [ ] Task 1, [ ] Task 2

## Midday Check-In
- **Progress**: [Brief summary]
- **Challenges**: [Brief description]

## End of Day Review
- **Achievements**: [Brief summary]
- **Findings**: [Key findings]
- **Next Steps**: [Plans for next day]

## Notes & Ideas
- [Any additional notes or ideas]

---