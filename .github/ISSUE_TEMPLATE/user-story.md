---
name: Stakeholder Template
about: This template is for creating stakeholder stories
title: ''
labels: ''
assignees: ''

---

### Stakeholder Story

**As a** [role]  
 **I need** [function]  
 **So that** [benefit]  

```example
As a Customer Support Manager
I need a dashboard that shows real‑time ticket volume and agent workload
So that I can redistribute tasks quickly and maintain our response‑time SLAs
```

### Details and Assumptions
* [document what you know]

```example
* The dashboard will pull data from Zendesk every 60 seconds
* Managers should be able to filter by team, shift, and ticket priority
* Only managers and supervisors have access
```

### Acceptance Criteria

```gherkin
Given [specific context]
When [specific action]
Then [specific outcome]
```

```example
Given I am logged in as a Customer Support Manager
And there are active tickets assigned across multiple agents
When I open the "Live Support Dashboard"
Then I see the total number of open tickets, grouped by priority
And I see each agent’s current ticket count and status
And the data refreshes automatically every 60 seconds
```
