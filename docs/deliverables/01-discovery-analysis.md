# Part 1: Process Discovery Analysis

← [Back to overview](../README.md) · Case: [scenario and transcript](../case/scenario.md)

**Labels used:** statements from the transcript are facts. Anything inferred is marked **[Assumption]**. Anything not covered in the session is marked **[Unknown]**. Gap numbers (e.g. "Gap 9") refer to section 1B in [01-discovery-analysis.md](01-discovery-analysis.md).

## 1A. Process Summary

### Purpose of the process
Take a potential client from first contact to a signed engagement, deliver the work, keep the client informed and bill for it.

Michael's goal: one standard delivery process "from sales through project completion", so the team spends less time coordinating and chasing information and more time delivering value.

### Key stakeholders

| Stakeholder | Role in the process (as described) |
|---|---|
| Michael Reynolds, Managing Partner | Runs some discovery calls, usually writes the proposal, sometimes assigns work directly for high-priority clients |
| Consultants | Run some discovery calls, deliver the work, are expected to update Asana weekly, submit time entries on hourly projects |
| Senior consultants | Sometimes write their own proposals |
| Project manager (PM) | Creates the project in Asana, sets up shared folders, usually assigns tasks by availability and expertise |
| Accounting | Generates invoices for hourly projects from time entries |
| Client | Reaches out, joins the discovery call, approves or asks to revise the proposal, signs the agreement, receives updates |

Not named **[Unknown]**: who watches incoming inquiries and replies first, and who sends fixed-fee invoices.

### Systems and tools referenced

| Tool | Used for (as described) | Consistency |
|---|---|---|
| HubSpot | Logging leads | Not always used. Fast-moving referrals are sometimes not logged |
| Asana | Projects, tasks, progress tracking, some documentation | Some consultants update through Slack or email instead |
| Shared folders | Project files, set up by the PM | Location not named. Google Drive **[Assumption]** |
| Google Drive | Some documentation | One of three places documents end up |
| Spreadsheet | Tracking consultant capacity ("mostly") | No formal resource planning system |
| Slack | Informal progress updates | Used in place of Asana by some consultants |
| Email | Progress updates and some documentation | Used in place of Asana by some consultants |
| LinkedIn and the website | Lead sources (with referrals) | |

Never named **[Unknown]**: the proposal tool, the agreement or e-signature tool, the time-tracking tool and the invoicing or accounting system.

### Major process stages
1. **Lead arrives:** "most clients" reach out through a referral, LinkedIn or the website. All of this is inbound. Outbound sales was not mentioned.
2. **First response and scheduling [Unknown]:** someone must reply to the inquiry and book the discovery call. Who does this, through which channel and how fast was not covered. The HubSpot entry, if made, probably happens here **[Assumption]**.
3. **Discovery call:** Michael or a consultant learns the client's needs.
4. **Fit decision:** "if it looks like a fit", a proposal is prepared.
5. **Proposal:** usually written by Michael, sometimes by a senior consultant. "The format is mostly the same, although everyone has their own approach."
6. **Proposal review:** the proposal is sent, then the firm waits for approval. Sometimes the client asks for revisions.
7. **Agreement:** the client signs an agreement.
8. **Handoff, kickoff and project setup:** a kickoff meeting is scheduled (by whom is **[Unknown]**) and the PM creates the Asana project and shared folders. How the PM learns the deal is signed, and the order of these steps, are **[Unknown]**. This is the "intended process". Consultants sometimes start work before setup is finished.
9. **Work assignment:** the PM usually assigns tasks by availability and expertise, using the capacity spreadsheet. Michael sometimes assigns directly for high-priority clients.
10. **Delivery and progress tracking:** consultants are expected to update Asana weekly. Some update through Slack or email instead.
11. **Client updates:** typically weekly status meetings. Some clients want written reports, others a quick call.
12. **Billing:** fixed-fee projects are usually invoiced monthly. On hourly projects, consultants submit time entries and accounting generates invoices. Sometimes time entries come in late, which delays billing.
13. **Completion [Unknown]:** named as the end of the process but never described. It could mean the final deliverable is accepted, the contract term ends or the final invoice is paid. It likely differs between fixed-fee and hourly work.

### Inputs and outputs

| Stage | Inputs | Outputs |
|---|---|---|
| 1. Lead arrives | Inquiry through a referral, LinkedIn or the website | A lead the firm knows about |
| 2. First response | The inquiry | Discovery call booked. HubSpot record, sometimes |
| 3. Discovery call | Booked call, the client's stated needs | Understanding of needs. Whether notes are recorded, and where, is **[Unknown]** |
| 4. Fit decision | Discovery call outcome | Go to proposal, or not a fit (handling **[Unknown]**) |
| 5. Proposal | Discovery outcome **[Assumption]**, author's own approach. Pricing inputs **[Unknown]** | Proposal document |
| 6. Proposal review | Proposal, client feedback | Accepted proposal, or a revision request back to stage 5. Rejection handling **[Unknown]** |
| 7. Agreement | Accepted proposal | Signed agreement |
| 8. Handoff, kickoff and setup | Signed agreement (how it reaches the PM is **[Unknown]**) | Kickoff meeting scheduled, Asana project, shared folders |
| 9. Work assignment | Asana project, capacity spreadsheet, consultant expertise | Tasks assigned to consultants |
| 10. Delivery and tracking | Assigned tasks | Work product, progress updates (Asana, Slack or email), time entries on hourly projects |
| 11. Client updates | Project status, the client's preferred format | Status meeting, written report or call |
| 12. Billing | Fixed fee: monthly schedule from the agreement **[Assumption]**. Hourly: consultants' time entries | Invoice. Payment collection **[Unknown]** |
| 13. Completion | **[Unknown]** | **[Unknown]** |

### Decision points
1. **Log the lead in HubSpot?** Sometimes skipped when it's a referral and "we're moving quickly". There is no rule.
2. **Who runs the discovery call?** Michael or a consultant. The criteria are **[Unknown]**.
3. **Is the client a fit?** If yes, a proposal is prepared. The fit criteria and what happens to a no-fit lead are **[Unknown]**.
4. **Who writes the proposal?** Usually Michael, sometimes a senior consultant. When each one does is **[Unknown]**.
5. **Does the client accept the proposal?** Accept leads to the agreement. Revisions loop back to the proposal. Rejection is **[Unknown]**.
6. **Start work before setup is complete?** Happens when the client wants to move quickly. Who allows it is **[Unknown]**.
7. **Who assigns the work?** Usually the PM. Michael for high-priority clients. "High priority" is not defined.
8. **What update format does the client get?** Meeting, written report or call. Who decides, and when, is **[Unknown]**.
9. **Fixed fee or hourly?** Decides the billing path: a monthly invoice, or invoicing from time entries.

---

## 1B. Information Gaps

### Missing information (not covered in the session)

| # | Stage | What we don't know | Why it matters |
|---|---|---|---|
| 1 | First response | Who watches the inbound channels (website form, LinkedIn, referral emails), and how fast they reply | A slow first reply loses leads. With no owner, it's nobody's job to reply |
| 2 | Lead tracking | Lead volume per month, and how many leads never reach HubSpot | Shows how large the HubSpot gap is and whether pipeline reports can be trusted |
| 3 | Discovery call | Whether notes are taken, in what format and where they're stored | The proposal and the delivery team both depend on what was learned on this call |
| 4 | Fit decision | The criteria for a fit (budget, service type, size, timing) and what happens to no-fit leads | Without criteria, two people can judge the same lead differently |
| 5 | Proposal | Whether a template exists, how pricing is set, who reviews or approves before sending, and the tool used | "Mostly the same format" could mean a shared template or just habit |
| 6 | Proposal review | Typical number of revision rounds, how long approval takes, follow-up when a client goes quiet, rejection handling | Shows where deals stall |
| 7 | Agreement | Who drafts the agreement, whether it's a standard contract or custom, and the signature tool | The signed agreement is what's meant to start project setup |
| 8 | Handoff | How the PM learns a deal is signed, and what information is passed from sales to delivery | This is the point where client context is most likely to get lost |
| 9 | Kickoff | Who schedules and runs it, the agenda, and whether it comes before or after Asana and folder setup | The order in the transcript is unclear |
| 10 | Early starts | How often work starts before setup, and what's missing when it does (Asana project, folders, signed agreement?) | The transcript only says "before everything is fully set up". If that can include before the agreement is signed, it's a billing and legal risk |
| 11 | Assignment | What the capacity spreadsheet tracks, who updates it and how often | Assignments are only as good as this spreadsheet |
| 12 | Progress tracking | What a complete weekly Asana update includes, whether anyone checks it, and why some consultants prefer Slack or email | Expectations without a check, or Asana being harder to use, may explain the drift **[Assumption]**. The fix depends on which one it is |
| 13 | Client updates | Who prepares reports, who decides the format, and whether it's set at kickoff | The work behind each update format is unknown |
| 14 | Billing | The time-tracking and invoicing tools, the time-entry deadline, who sends fixed-fee invoices, how payment is collected and followed up | Late time entries already delay billing |
| 15 | Completion | What "complete" means (deliverables accepted, final invoice paid, contract end), and any closeout steps: sign-off, final report, file archive, feedback | Michael wants a process "through project completion", but that end point isn't defined |
| 16 | Scale | Team size: number of consultants, PMs and accounting staff, and the number of active projects | Changes which fixes make sense |
| 17 | Engagement types | Fixed-fee vs. hourly split, and whether other types exist (retainers, milestone billing) | Billing and completion depend on the type |
| 18 | Documentation | Which documents a project produces (proposal, agreement, notes, reports, deliverables) and where each is supposed to live | Michael named scattered documentation as a core problem, but no standard was described to measure against |
| 19 | Baseline metrics | Any current numbers: time from inquiry to proposal, proposal win rate, invoice delay, hours per week spent coordinating | Without a baseline, the effect of any improvement can't be shown |
| 20 | Changes during delivery | How scope changes, extra work, pauses or cancellations are handled and approved | Common in consulting and directly affects billing. Not mentioned at all |

### Unclear responsibilities or ownership

| Activity | Who it could be | What's unclear |
|---|---|---|
| Replying to new inquiries | Michael, a consultant or someone else | Not mentioned at all |
| Running the discovery call | "Either I or one of our consultants" | How it's decided |
| Logging leads in HubSpot | Whoever takes the call **[Assumption]** | No one is named, and skipping is allowed |
| Writing the proposal | Michael, usually. Senior consultants, sometimes | When a senior consultant writes it, and whether Michael reviews it |
| Approving pricing and terms | Michael **[Assumption]** | Not discussed |
| Telling the PM a deal is signed | Unknown | No handoff owner |
| Allowing an early start | Unknown | It "happens". No one is named as approving it |
| Assigning work | PM, usually. Michael for high-priority clients | Who decides a client is "high priority", and whether the PM is told when Michael assigns directly |
| Keeping the capacity spreadsheet current | Unknown | Not discussed |
| Making sure Asana is updated | PM **[Assumption]** | "Consultants are expected to", but no one enforces it |
| Preparing client updates and reports | PM or consultant **[Assumption]** | Not discussed |
| Chasing late time entries | Unknown | Late entries delay billing, but no one is named to chase them |
| Sending fixed-fee invoices | Accounting **[Assumption]** | Only hourly invoicing is tied to accounting |
| Deciding a project is complete | Unknown | Not discussed |
| Owning the overall process | Michael **[Assumption]** | No process owner is named |

### Assumptions I'm making (not yet validated)

1. The shared folders the PM creates are in Google Drive.
2. The proposal is based on what was learned in the discovery call.
3. Michael approves pricing and terms, including proposals written by senior consultants.
4. The kickoff meeting includes the client.
5. The fixed-fee monthly invoice amount comes from the signed agreement.
6. Accounting is a person or team separate from the consultants.
7. Asana and Google Drive are the intended homes for project tracking and documents. Slack and email are workarounds.
8. The engagement types are fixed-fee and hourly only.
9. "Completion" happens once per project, not per phase or deliverable.
10. The firm is small enough that Michael is involved in day-to-day decisions. He writes most proposals and assigns some work himself.

---

## 1C. Follow-Up Questions

These are for a 45 to 60 minute follow-up session. Each question builds on something Michael already told us, and the gap numbers point back to 1B. Ideally the PM, one consultant and someone from accounting join for part of the session, since several answers sit with them.

### Lead intake and first response
1. When an inquiry comes in through the website or LinkedIn, where does it land, and who sees it first? (Gap 1)
2. Who replies and books the discovery call? Roughly how long does that take today? (Gap 1)
3. About how many new inquiries do you get in a month? How many of them come from referrals? (Gap 2)
4. When a referral moves fast and skips HubSpot, does it ever get added later? If not, how do you know what's in your pipeline? (Gap 2)

### Discovery and fit
5. How do you decide whether you or a consultant takes the discovery call? (Ownership)
6. What makes a client "a fit"? Can you give a recent example of one you turned down, and why? (Gap 4)
7. What happens to a lead that isn't a fit? Do you refer them elsewhere, keep them in HubSpot, or drop them? (Gap 4)
8. Are notes from the discovery call written down? If so, where do they live, and who reads them later? (Gap 3)

### Proposal and agreement
9. You said the format is "mostly the same". Is there a shared template, or do people start from an old proposal? (Gap 5)
10. How is pricing set, and how is fixed-fee vs. hourly chosen? Who signs off on the price before a proposal goes out? (Gap 5, Gap 17)
11. When a senior consultant writes a proposal, do you review it before it's sent? (Ownership)
12. On average, how many revision rounds does a proposal go through, and how long until a client decides? What do you do when a client goes quiet? (Gap 6)
13. Who prepares the agreement? Is it a standard contract, and which tool is used for signatures? (Gap 7)

### Handoff, kickoff and setup
14. Once a client signs, how does the PM find out? What information do they get from whoever sold the deal? (Gap 8)
15. Does kickoff happen before or after the Asana project and folders are set up? Who runs it? (Gap 9)
16. When consultants start early, what's usually missing: Asana, folders, the kickoff, or even the signed agreement? Who agrees to the early start? (Gap 10)
17. Roughly how often does work start before setup is complete? (Gap 10)

### Assignment and capacity
18. What does the capacity spreadsheet track (hours, projects, skills)? Who updates it, and how often? (Gap 11)
19. What makes a client "high priority"? When you assign work directly, is the PM told, and does the spreadsheet get updated? (Ownership)

### Delivery, tracking and client updates
20. What should a weekly Asana update include? Does anyone check that it happened? (Gap 12)
21. Why do some consultants send updates through Slack or email instead? Is something about Asana getting in the way? (Gap 12)
22. Where is each type of document supposed to live, such as notes, deliverables and client reports? (Gap 18)
23. Who decides the client update format, and when? Who writes the written reports, and roughly how long does each one take? (Gap 13)

### Billing and completion
24. Which tools do you use for time tracking and invoicing? (Gap 14)
25. Is there a deadline for time entries? When they're late, who chases them, and how long does that usually delay an invoice? (Gap 14)
26. Who sends fixed-fee invoices, and who follows up on unpaid invoices? (Gap 14, Ownership)
27. How do you know a project is finished? Is there a client sign-off, a final invoice, or a closeout step such as archiving files or asking for feedback? Is it different for fixed-fee and hourly projects? (Gap 15)

### Scale and priorities
28. How many consultants, PMs and accounting staff do you have, and how many projects are usually active at once? (Gap 16)
29. Where do you feel the most time is lost to coordinating and chasing? Do you have any numbers, even rough ones? (Gap 19)
30. When a client asks for extra work or the scope changes mid-project, what happens? Who approves it, and how does it reach billing? (Gap 20)
31. Who would own a standardized process once it's defined? (Ownership)

### Documents to request before the next session
- 2 or 3 recent proposals from different authors, to see how much the format really varies
- A sample agreement
- A view of the capacity spreadsheet
- Two active Asana projects: one well kept, and one that isn't
- A recent client status report
- A recent invoice and the time entries behind it, for an hourly project
