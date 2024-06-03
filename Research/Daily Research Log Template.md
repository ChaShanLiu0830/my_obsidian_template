---
title: "<% tp.date.now("YYYY-MM-DD") %> - Daily Research Log"
date: <% tp.date.now("YYYY-MM-DD") %>
tags: [daily_notes, research, <%  tp.file.folder(true).split('/').slice(-2, -1)[0].replace(/[-\s]/g, '_').toLowerCase()%>  ]
status: [In Progress, Completed]
---
<%*
const parentFolderName = tp.file.folder(true).split('/').slice(-2, -1)[0];
const todayDate = tp.date.now("YYYY-MM-DD");
await tp.file.rename(`${todayDate} - Daily Research Log`);
%>

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