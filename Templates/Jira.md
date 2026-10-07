<%*
const JIRA = "https://jira.com/ticket/";
const key = tp.file.title;
const url = JIRA + key;
tR += `---
tags:
  - jira
related:
url: ${url}
---
# ${key}

[${key}](${url})

## Notes
`;
%>
