# Part 3: Process Improvement and AI Opportunities

← [Back to overview](../README.md) · Case: [scenario and transcript](../case/scenario.md)

**Labels used:** statements from the transcript are facts. Anything inferred is marked **[Assumption]**. Anything not covered in the session is marked **[Unknown]**. Gap numbers (e.g. "Gap 9") refer to section 1B in [01-discovery-analysis.md](01-discovery-analysis.md).

## 3A. Operational Challenges

Ordered by business impact. Each one traces back to the transcript.

| # | Challenge | Evidence from discovery | Risk |
|---|---|---|---|
| C1 | **No single process owner, and no checks at handoffs** | Responsibilities shift case by case (proposals, assignment, setup, updates). No one checks that steps happen | This is the root cause behind most of the items below. The process depends on individual habits |
| C2 | **Late time entries delay billing** | "Sometimes time entries come in late, which delays billing" | Cash flow and revenue. This is the only issue Michael tied directly to money |
| C3 | **No clean sales-to-delivery handoff** | No handoff described. Work sometimes starts before Asana and folders exist | Client context gets lost. Work isn't tracked from day one. Possible unbilled or unapproved work if it ever starts before signing **[Assumption]** |
| C4 | **Project status is spread across Asana, Slack and email** | "Some provide updates through Slack or email instead" | The PM and Michael have no single view of where projects stand. Time is spent chasing updates |
| C5 | **Documents have no single home** | "Sometimes it's in Asana, sometimes Google Drive, sometimes email" | Time lost searching. Knowledge is lost when people leave. Harder to onboard new consultants |
| C6 | **Incomplete pipeline data** | Fast referrals are sometimes not logged in HubSpot | Pipeline reports can't be trusted. Lead history and follow-ups can be lost |
| C7 | **Proposals vary by author** | "Everyone has their own approach". Michael writes most of them | Inconsistent client experience. Michael is a bottleneck on new revenue |
| C8 | **Capacity is managed in a spreadsheet, outside the main tools** | No resource planning system. Michael sometimes assigns work directly | Over- or under-allocation. The spreadsheet may not reflect Michael's direct assignments **[Assumption]** |
| C9 | **Client updates aren't standardized** | Meetings, written reports or calls, depending on the client | Different effort for each client, and no guaranteed level of service |
| C10 | **Undefined start and end of the process** | First response and completion were never described | Leads can go unanswered. Projects may never be formally closed, signed off or archived |

**The common thread:** the tools are already in place (HubSpot, Asana, Drive, Slack). What's missing is **rules, owners and connections between those tools**. That's good news, because most fixes don't need new software.

## 3B. Improvement Recommendations

Process fixes come first, because automating an undefined process just makes the inconsistency happen faster.

| Priority | Recommendation | Fixes | Effort |
|---|---|---|---|
| **1. Now** | **Define the standard process and name an owner for each stage.** Use the workflow in Task 2 as the starting point, validate it in the next session, and assign one owner per stage (first response, handoff, setup, client updates, billing follow-up, closeout) | C1, C3, C10 | Low |
| **2. Now** | **Set four non-negotiable rules:** (1) every lead goes into HubSpot, (2) no work starts until the Asana project exists, or the PM approves an early start, (3) Asana is where project status lives, (4) time entries are due by a fixed day each week | C3, C4, C6, C2 | Low |
| **3. Now** | **One document standard:** a fixed Google Drive folder template for every client (Sales / Contract / Delivery / Reports / Billing), linked from the Asana project. Nothing lives only in email | C5 | Low |
| **4. Next** | **A sales-to-delivery handoff checklist:** signed agreement, scope, billing type, client contacts, update preference and discovery notes. The PM confirms it before kickoff | C3, C9 | Low |
| **5. Next** | **A standard proposal template** with fixed sections and pricing blocks. Authors keep their own voice in the summary only | C7 | Medium |
| **6. Next** | **Agree the client update format at kickoff** (one of three standard options) and record it in Asana | C9 | Low |
| **7. Later** | **Define "complete"** for fixed-fee and hourly projects, with a closeout checklist: client sign-off, final invoice, files archived, feedback requested | C10 | Low |
| **8. Later** | **Move capacity tracking into Asana**, or a tool connected to it, once the rules above are working, so direct assignments show up automatically | C8 | Medium |

**How to measure it:** set a baseline first (1B, Gap 19). Then track time from inquiry to first reply, the share of leads in HubSpot, days from month end to invoice, how many projects are set up before work starts, and how many projects have their documents in the standard folder.

## 3C. Automation and AI Opportunities

These build on the rules in 3B and use the tools the firm already has. The connections could be built in a workflow tool such as n8n, Zapier or Make, which all connect to HubSpot, Asana, Google Drive and Slack. The final choice depends on the tools not yet named (1B, Gap 14).

### 1. Automatic lead capture and first response
- **Current problem:** referrals sometimes skip HubSpot. Nobody owns the first reply, and response speed is unknown.
- **Proposed solution:** website form and LinkedIn inquiries create a HubSpot record automatically. For referrals, a forwarding address or a Slack command creates the record in seconds. AI drafts a short first reply and suggests discovery call times for the owner to review and send. If an inquiry has no reply after an agreed window, a Slack alert goes out.
- **Expected impact:** every lead is tracked, first replies are faster, and pipeline reports can be trusted.
- **Assumptions:** inquiries arrive in channels that can be connected (form, email). LinkedIn messages may still need manual entry. The firm agrees on a response-time target.

### 2. AI discovery call summary
- **Current problem:** we don't know whether discovery notes are recorded or where (1B, Gap 3). The proposal author and the delivery team depend on them.
- **Proposed solution:** record the call (with client consent), transcribe it, and have AI produce a structured summary: needs, scope, budget signals, timeline and fit indicators. The summary is saved to the HubSpot deal and later passed on in the handoff.
- **Expected impact:** client context is captured once and reused. Proposals start from real notes, and fit decisions are easier to compare.
- **Assumptions:** clients consent to recording, and calls happen on a platform that supports it (Zoom, Meet or Teams).

### 3. AI-assisted proposal drafting
- **Current problem:** proposals vary by author, and Michael writes most of them, so they wait on him.
- **Proposed solution:** combine the standard template (3B, item 5) with an AI first draft built from the discovery summary and past winning proposals. The author edits, and Michael reviews a consistent draft instead of writing from scratch.
- **Expected impact:** faster proposals, a consistent format, and senior consultants can take on more proposals with less of Michael's time.
- **Assumptions:** past proposals are available to learn from, and pricing rules can be written down. A person always reviews before anything is sent.

### 4. Automatic project setup when the deal is signed
- **Current problem:** no defined handoff. Setup is manual, and work sometimes starts before it's done.
- **Proposed solution:** when the HubSpot deal is marked "Closed Won", or the e-signature completes, an automation creates the Asana project from a template, creates the standard Drive folder, links the two, posts the handoff checklist to the PM in Slack, and drafts the kickoff invite.
- **Expected impact:** setup takes minutes instead of depending on someone's free time. Early starts become less likely to happen without setup, because the setup is already there.
- **Assumptions:** deal status in HubSpot is kept up to date. The e-signature tool (not yet named) can trigger the automation.

### 5. Status updates captured in one place, plus AI client reports
- **Current problem:** status is split across Asana, Slack and email, and client reports are written by hand in different formats.
- **Proposed solution:** (a) A weekly Slack nudge to each consultant links to their open Asana tasks. Updates posted in a project's Slack channel are added to Asana automatically. (b) AI drafts each client's weekly update from Asana activity, in the format agreed at kickoff (meeting agenda, written report or call notes). The PM reviews and sends it.
- **Expected impact:** a single view of status for the PM and Michael, less chasing, and consistent client updates with less writing.
- **Assumptions:** the firm accepts Asana as the single source of status. Project Slack channels exist or can be created.

### 6. Time-entry reminders and invoice preparation
- **Current problem:** late time entries delay hourly billing.
- **Proposed solution:** automated Slack reminders before the weekly deadline, a personal follow-up for anyone still missing entries, and a weekly report to the PM of projects with missing time. When entries are complete, invoice drafts are created for accounting to review. Fixed-fee invoices are drafted automatically each month from the agreement terms.
- **Expected impact:** fewer late entries, faster invoicing and better cash flow. This is the most directly measurable win.
- **Assumptions:** the time-tracking and invoicing tools (not yet named) have APIs or exports. A weekly deadline is agreed in 3B.

### 7. Operations dashboard and AI weekly digest
- **Current problem:** "When projects scale, it becomes harder to know whether everyone is following the same process."
- **Proposed solution:** a simple dashboard that pulls from HubSpot and Asana, showing open leads with no reply, proposals waiting, projects missing setup, overdue Asana updates, missing time entries and capacity. Each Monday, AI writes a short digest for Michael that highlights exceptions only.
- **Expected impact:** Michael can see in a few minutes whether the process is being followed, without chasing people.
- **Assumptions:** recommendations 1 to 6 are in place, so the data exists. Team size makes a dashboard worthwhile (1B, Gap 16).

### Suggested order
1. **Weeks 1 to 2:** 3B rules and owners, plus quick automations #1 (lead capture) and #6 (time-entry reminders). These are low effort and the impact is visible right away.
2. **Weeks 3 to 6:** #4 (project setup) and #5 (status capture and client reports), after the handoff checklist and folder template are agreed.
3. **Later:** #2 and #3 (AI on discovery calls and proposals) and #7 (dashboard), once the data and templates are consistent.

**Principle throughout:** AI drafts and people approve. Nothing goes to a client without review.
