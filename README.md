**Stage Definitions:**

| Stage | Definition | Owner |
|---|---|---|
| New | Ticket just received, unassigned | System |
| Open | Assigned to agent, in progress | Agent |
| Pending | Awaiting customer response | Customer |
| On Hold | Awaiting internal team action | Agent |
| Resolved | Solution provided, awaiting confirmation | Agent |
| Closed | Customer confirmed resolution | System |

## Ticket Categories and Priority Levels

**Categories:**
- Billing and Payments
- Account Management
- Technical Issues
- Product Enquiries
- Complaints and Escalations
- KYC and Verification
- Refunds and Disputes

**Priority Levels:**

| Priority | Criteria | Response Time |
|---|---|---|
| Low | General enquiries, feedback | 24 hours |
| Medium | Account issues, billing questions | 8 hours |
| High | Service disruptions, failed transactions | 4 hours |
| Urgent | Security issues, account compromise | 1 hour |

## HubSpot Workflow Setup

**Workflow 1 — New Ticket Auto Assignment**
- Trigger: New ticket received
- Action: Auto assign to available agent
- Condition: Based on ticket category
- Notification: Agent receives email and in-app alert

**Workflow 2 — SLA Breach Warning**
- Trigger: Ticket approaching SLA deadline
- Action: Send warning notification to agent
- Condition: 1 hour before SLA breach
- Escalation: Auto notify Team Lead if breached

**Workflow 3 — Customer Follow Up**
- Trigger: Ticket in Pending status for 24 hours
- Action: Send automated follow up to customer
- Condition: No customer response received
- Close: Auto close if no response after 72 hours

**Workflow 4 — Escalation Trigger**
- Trigger: Ticket marked High or Urgent
- Action: Notify Team Lead immediately
- Condition: Priority level change
- Response: Team Lead acknowledges within 30 minutes

**Workflow 5 — CSAT Survey**
- Trigger: Ticket marked Closed
- Action: Send automated CSAT survey to customer
- Condition: All closed tickets
- Tracking: Responses logged in HubSpot dashboard

## Response Time Structure

| Channel | First Response | Resolution |
|---|---|---|
| Email | 2 hours | 24 hours |
| WhatsApp | 1 hour | 8 hours |
| Phone | Immediate | Same day |
| Social Media | 1 hour | 8 hours |

## Ticket Macros and Templates

**Macro 1 — General Acknowledgement**
> "Thank you for reaching out. I have received 
your request and will get back to you within 
[timeframe]. Your ticket reference is [REF]."

**Macro 2 — Pending Customer Response**
> "I hope this message finds you well. I am 
following up on your recent request [REF]. 
Could you please provide [information needed] 
so I can resolve this for you promptly?"

**Macro 3 — Resolution Confirmation**
> "I am pleased to confirm that your issue 
has been resolved. Please do not hesitate 
to reach out if you need further assistance."

**Macro 4 — Escalation Acknowledgement**
> "I understand the urgency of your situation. 
I have escalated your case to our specialist 
team who will contact you within [timeframe]. 
Your reference number is [REF]."

**Macro 5 — Ticket Closure**
> "Your ticket [REF] has been closed following 
resolution. We would appreciate your feedback 
on your experience. Please complete our short 
survey: [LINK]."

## CRM Best Practices
- Log every customer interaction immediately after contact
- Update ticket status at every stage of resolution
- Add detailed notes to every ticket for team visibility
- Never close a ticket without customer confirmation
- Tag tickets correctly for accurate reporting
- Use macros to maintain consistency across all responses
- Review open tickets daily to prevent SLA breaches
- Escalate immediately when resolution is outside your scope

## Reporting and KPI Tracking

**Weekly Reports to Track:**

| Metric | Target | Frequency |
|---|---|---|
| CSAT Score | 90%+ | Weekly |
| First Contact Resolution | 70%+ | Weekly |
| Average Handle Time | Reduce monthly | Weekly |
| SLA Compliance | 95-100% | Weekly |
| Net Promoter Score | Positive trend | Monthly |
| Ticket Volume | Monitor trends | Weekly |

**How to Pull Reports in HubSpot:**
- Go to Reports dashboard
- Select Customer Support report
- Filter by date range, agent or ticket category
- Export to CSV for further analysis
- Share with Team Lead every Monday

## Common CRM Mistakes to Avoid
- Leaving tickets in Open status without updates
- Closing tickets without customer confirmation
- Not logging interactions immediately
- Using wrong ticket category or priority level
- Missing SLA deadlines without escalating
- Not adding notes when handing over tickets
- Sending responses without personalisation
- Ignoring CSAT survey results

## Tools Used

**Primary CRM:**
[HubSpot](https://www.hubspot.com) — tickets, 
workflows, reporting and customer management

**Additional CRM & Ticketing Tools:**
[Zendesk](https://www.zendesk.com) — tickets, 
workflows and reporting |
[Freshdesk](https://www.freshdesk.com) — tickets, 
workflows and reporting |
[Zoho CRM](https://www.zoho.com/crm) — tickets, 
workflows and reporting

**Collaboration & Productivity:**
[Notion](https://www.notion.so) | 
[Slack](https://slack.com)

Also experienced working with proprietary 
in-house CRM and ticketing systems in 
high volume Telecom environments.
