# Full business audit — Cockpit Builder

Understand the whole operation before choosing what to improve. Give this file to the assistant you already use along with any approved existing context. Say: “Run the full business audit with me, one question at a time.” You can pause and resume. If you want a shorter start, say “Run the quick start”; it is a partial audit.

The full path covers 8 areas and 57 prompts with conversational follow-ups. The quick path covers 10 starting prompts. Reuse known answers; do not fill everything again. Additional business-specific questions may be needed. No private records, new account or paid tool is required to begin.

## Source and adaptation

High Ticket Sales Framework — joshcollier.ai: https://joshcollier.ai/resources/sales-framework
Reviewed 2026-10-06. Adapted from the Sales Framework source: Power Close, Qualification, Discovery, Business Numbers and Technical Audit. Operations extensions are marked separately. The public URL was reachable; the local source supplied the question text.
Source IDs preserve the connection to the original questions. “extension” identifies added delivery, economics, team and operating-control questions. The source’s sales close is not part of this self-audit, and its “money left on the table” exercise is replaced with evidence-based calculations and clearly labeled scenarios.

## Instructions for your assistant

Use the Cockpit Builder business audit to understand my operation before recommending tools.

Read my existing context and answers first. Confirm which business and offer we are auditing. Ask whether I want the full audit or quick start. If I explicitly requested a full audit, begin it without asking again. If I have not chosen, offer full audit as the recommended path. Quick start uses only questions marked Quick start and must be labeled partial; it is not a completed full audit.

Ask one short question at a time, splitting multi-part prompts into conversational follow-ups. Explain unfamiliar words, skip facts already supplied, and accept unknown, approximate, not applicable or prefer not to share. Do not dump the question bank at me. Briefly summarize each section so I can correct it before continuing.

Adapt to my situation: for a pre-revenue business, record hypotheses and ask about customer validation instead of inventing sales metrics. Use relevant branches for services, products, subscriptions and local businesses. For multiple businesses, audit each separately and keep ownership, numbers and data separate. Do not require new software or account access just to finish the interview. Never request passwords, API keys, raw customer/patient records or bank documents. If I volunteer secret values, omit them from output.

Capture question ID, my answer, business/offer, period/date, source, whether owner-reported or independently verified, and any follow-up needed in BUSINESS-AUDIT-ANSWERS.md. Track answered, unknown, not applicable, skipped and deferred separately. Preserve my exact meaning and earlier instructions; do not replace richer facts. If I pause, return an unsaved checkpoint or save only in my approved location: scope, mode, answers, section position and next unanswered question. Resume from it without restarting.

Use the bank below. The source IDs refer to the linked Sales Framework; extension marks added operations coverage. Adapted qualification questions identify implementation constraints, not an obligation to buy. Do not use pressure, objection manipulation or the sales closing script.

When the chosen path is covered, produce BUSINESS-AUDIT.md with:
- Scope, date, mode and coverage: what was answered, unknown, skipped, deferred or not applicable. Label incomplete work honestly.
- Current state, desired 90-day/six-month outcome, and evidence-backed gaps.
- A business map: owner → business → offer → buyer → channels → sales → delivery → retention; mark missing steps.
- A process map with each step, responsible person, tool, input, output, handoff and acceptance check.
- A dated metrics table with units, currency, period, source and confidence. Keep leads and customers from the same group and period for conversion rates. Different cohorts cannot be divided as if matched.
- Prioritized improvements: problem, evidence, suggested change, owner to confirm, dependencies, effort estimate, expected benefit/assumptions and verification check. Include what to keep or stop. Mark priority/effort as judgments, not measured facts.
- A practical 30-day plan and 90-day milestones with owners, dates to confirm and success measures. No invented commitments.
- Open questions and one useful draft or small authorized test to complete first.

Then use the included BUSINESS-REPORT-PROMPT.md to turn the supported findings into BUSINESS-COCKPIT-REPORT.md, EVIDENCE-LEDGER.md and ACTION-PLAN.md. Read or attach the actual prompt text; naming a file does not give you access to it. Preserve BUSINESS-AUDIT.md and the private answer record. Match report depth to the available evidence; skipped answers remain unknown, and quick start remains partial. For client discovery, keep the prospect's data separate and validate assumptions before a proposal. PDF delivery depends on your assistant's document tools; otherwise provide complete Markdown to save.

Calculate only from supplied, comparable figures and show formulas. Never claim an exact amount of lost revenue or guaranteed return from missing data. Do not invent industry benchmarks. Label hypothetical uplift as a scenario, separate revenue from profit and cash, avoid double-counting the same lead across gaps, and state missing costs. If a denominator is zero or unknown, report the metric unavailable. Annualizing a monthly scenario is an assumption, not a forecast. The audit is an operational self-assessment, not a financial, legal or security certification.

Ask me to review the findings. After approval, propose merging durable facts into LLM.md and active decisions into BRAIN.md without overwriting existing work. Share only my approved summary via the shared-brain guide; keep raw audit answers private by default. Report drafted, saved and verified separately. Do not send, spend, publish, install, delete or connect accounts without authorization.

## Question bank

## Current reality and goals

Understand where the business is, where the owner wants it to go, and what prevents progress.

- **direction-1 · Quick start** — Which business and offer are we auditing, who buys it, and what stage is it at? _(Source: bn-q1)_
- **direction-2 · Quick start** — What is not working right now? Give one recent example. _(Source: q-q1, q-q2, pc-q1)_
- **direction-3** — What are you doing about it now, and what have you already tried? _(Source: pc-q2, q-q9)_
- **direction-4 · Quick start** — What outcome do you want in 90 days, six months and a year? Start with the nearest milestone. _(Source: q-q3, q-q4, pc-q3)_
- **direction-5** — What would improving this in the next 30 days change in your working week? _(Source: pc-q4)_
- **direction-6** — What is stopping you, and what happens if nothing changes? Separate measured cost from your concerns. _(Source: pc-q1, pc-q5, q-q10)_
- **direction-7** — What alternatives are you considering, and what would make a solution a good fit? _(Source: q-q5, q-q12)_

## Customers, offers and proof

Check who the business serves, what it sells, and how it knows the offer works.

- **offer-1** — What do customers purchase most often, and what result are they buying? _(Source: d-q4, bn-q1)_
- **offer-2 · Quick start** — What do you charge, what is included, and how/when do customers pay? Identify currency and price changes. _(Source: d-q5, bn-q2)_
- **offer-3** — How many active clients do you serve, and how many purchases happened in the last complete month? _(Source: bn-q3)_
- **offer-4** — What three questions tell you whether a lead is a good fit? _(Source: d-q11, d-q12, d-q13)_
- **offer-5** — Why do customers choose you rather than alternatives, and what evidence supports that? _(Source: t-q8)_
- **offer-6** — What objections, complaints, refunds or reasons for leaving appear repeatedly? _(Source: extension)_
- **offer-7** — What customer proof do you have permission to use, and what claims remain unproven? _(Source: extension)_

## Marketing, leads and sales

Map how interest turns into customers and where follow-up breaks down.

- **pipeline-1 · Quick start** — Which channels bring leads today, who owns each, and which actually bring customers? _(Source: d-q1, bn-q5)_
- **pipeline-2 · Quick start** — How many leads arrived in the last complete month, and how many of those became customers? Use the same group and period. _(Source: d-q2, d-q3, bn-q6, bn-q8)_
- **pipeline-3** — How much did you spend on advertising in that period, and what results can you attribute to it? _(Source: bn-q9)_
- **pipeline-4 · Quick start** — Who follows up with new leads and people who do not buy? _(Source: d-q6)_
- **pipeline-5** — How quickly do you respond, and how many follow-up attempts happen before a lead is closed? _(Source: d-q7, d-q8)_
- **pipeline-6** — Do shopping-around calls or missed calls occur? What counts and outcomes can you actually measure? _(Source: d-q9, d-q10)_
- **pipeline-7** — Walk through one recent lead from first contact to payment. Where did it stall or require retyping? _(Source: t-q6)_
- **pipeline-8** — How large is your contact database, and which records may you lawfully contact through each channel? _(Source: bn-q7, extension)_
- **pipeline-9** — How many people sell, what stages do they use, and how are handoffs, outcomes and pipeline reviews recorded? _(Source: bn-q4, t-q6)_

## Delivery and customer retention

Follow the work after a sale and identify delays, capacity limits and repeat business.

- **delivery-1 · Quick start** — Walk through onboarding, delivery, approval and support for one typical customer. _(Source: extension)_
- **delivery-2** — Who owns each step, and what tells the next person that it is ready? _(Source: extension)_
- **delivery-3** — Where do tasks stall, get repeated, get lost or depend on the owner being available? _(Source: extension)_
- **delivery-4** — How much work can you deliver with your current team before quality or deadlines suffer? _(Source: extension)_
- **delivery-5** — What checks confirm the promised result, and how do you handle problems or rework? _(Source: extension)_
- **delivery-6** — How do you measure retention, renewals, repeat purchases, referrals or churn where relevant? _(Source: extension)_
- **delivery-7** — Which operating instructions exist, where are they kept, and when were they last tested? _(Source: extension)_

## Business economics and cash flow

Establish dated numbers without guessing profitability or lost revenue.

- **economics-1** — What revenue was collected in the last complete month, and what is the reliable source? An approximate range is fine. _(Source: extension)_
- **economics-2** — What direct costs go into delivering the core offer, including paid labor and software usage? _(Source: extension)_
- **economics-3** — What recurring overhead, subscriptions and other commitments does the business carry? _(Source: extension)_
- **economics-4** — What unpaid invoices, payment delays, refunds or seasonal swings affect cash flow? _(Source: extension)_
- **economics-5** — What are the largest measurable costs in money or time? Which numbers are estimates? _(Source: pc-q1, extension)_
- **economics-6** — What budget could you comfortably allocate to improvements, and what result would justify it? _(Source: q-q7)_
- **economics-7** — Which numbers do you review regularly, who prepares them, and what decisions do they inform? _(Source: extension)_

## Website, tools, data and AI

Check what is actually used, connected and working before recommending software.

- **systems-1** — What do people find when they search for your business and services? Is a Google Business Profile relevant to your model? _(Source: t-q1, t-q4)_
- **systems-2** — How do you request, monitor and respond to reviews? _(Source: t-q2)_
- **systems-3** — Walk through your website and its main customer action. What chat, tracking and automations are actually working? _(Source: t-q5)_
- **systems-4** — Which CRM, Google services and other core tools do you use, and where is customer/project data kept? _(Source: bn-q11, t-q7)_
- **systems-5** — If you send enough email for deliverability reporting, what do Postmaster or provider reports show? Otherwise mark this not applicable. _(Source: t-q3)_
- **systems-6 · Quick start** — Which AI assistants or automations do you use today, for which jobs, and what has been tested? _(Source: bn-q10)_
- **systems-7** — Which tools exchange data automatically, which require copying, and where does information get lost? _(Source: extension)_
- **systems-8** — Who owns the accounts and domains, how is access controlled, and how do you verify backups can be restored? Describe the process, not secret values. _(Source: extension)_
- **systems-9** — What sensitive data or customer commitments limit what can be shared with AI or automated? _(Source: extension)_

## Team, decisions and support

Make responsibility, available time and implementation limits explicit.

- **people-1** — Who does what today, and which decisions require a partner, manager or other approver? _(Source: q-q8, extension)_
- **people-2** — How much time and capacity can the team realistically put into improvements? _(Source: q-q6)_
- **people-3** — What should you keep doing personally, delegate, document or stop? _(Source: extension)_
- **people-4** — What support would help most: guidance, hands-on help, training or ongoing ownership? _(Source: q-q11)_
- **people-5** — What dependencies, commitments or approval requirements could prevent a change from starting? _(Source: pc-q6)_
- **people-6** — What must be true for you to trust a change enough to adopt it? _(Source: q-q12, extension)_

## Priorities and the first useful change

Turn the audit into an owned, testable plan rather than a shopping list.

- **action-1 · Quick start** — Which problem is most worth fixing first, and what evidence supports that choice? _(Source: extension)_
- **action-2** — What small change could we test using the people and tools already available? _(Source: extension)_
- **action-3** — Who will own it, what approvals are needed, and what date is realistic? _(Source: q-q6, q-q8, extension)_
- **action-4** — What baseline and observable result will tell us whether it worked? _(Source: extension)_
- **action-5** — What would make us stop, revise or expand the test? _(Source: extension)_

## Leave with something usable

Keep this guide unchanged. Save your findings separately as BUSINESS-AUDIT-ANSWERS.md and BUSINESS-AUDIT.md in your approved private working location. Use the included BUSINESS-REPORT-PROMPT.md, or copy the complete prompt at https://builder.futureprooffoundry.com/business-report-prompt.md, to create your Business Cockpit Report, evidence ledger and action plan. Say: “Create my Business Cockpit Report from what we have. Let me skip missing answers and show me what to fix first.” Review the summary, merge approved facts into your existing brain, then use SHARED-BRAIN-SETUP.md if you want other assistants to read the same approved context. Files produced in chat remain unsaved until saved and read back. This download is guidance; it has not audited your business or connected your tools.
