PlotFlow — Local Real Estate CRM

A local-first CRM built to replace Excel/Google Sheets lead tracking for real estate plot sales — designed around three ideas: never lose context on a lead, know which properties are actually in demand, and use your own sales data to become a better closer.

Built and used personally on real leads across Lonavala, Khopoli, Karjat, Pali, Goa, and Igatpuri before ever becoming a product for a team.


Why This Exists

Spreadsheets track data. They don't track history, demand, or performance. Notes get overwritten, re-calls happen on guesswork, and there's no feedback loop telling you what's actually working. PlotFlow fixes that by turning raw call and lead activity into three things a spreadsheet can't give you:


A full, never-overwritten history of every lead interaction
A live demand signal per property based on real buyer behavior
A personal performance feedback loop based on your own call data



Core Features


Lead Timeline — append-only activity log per lead (calls, notes, stage changes, brochures, site visits). Nothing is ever overwritten.
Property Demand Engine — real-time demand score per plot, based on enquiries, callbacks, site visits, and active interested leads.
Personal Performance Analytics — tracks calls made, connection rate, best call timings, best-performing locations, and average attempts to conversion.
Call Management — every call attempt logged with status, outcome, notes, and auto-flagging on repeated failed attempts.
Reminders / Re-call Queue — auto-generated and priority-sorted from call outcomes, so follow-ups are never missed or guessed.
Plot Inventory — live view of available properties with interested-lead counts per plot.
Dashboard — command-center view combining all of the above into daily-usable insight.
Daily Email Report — automated summary sent after 6 PM to key stakeholders with call volume, conversions, and trends.



Data Backbone


Google Sheets — live, two-way synced source of truth
Excel — used for import and export/backup only (not live-synced)



Status

Idea and scope are fully defined — see attached PRD for full module breakdown and specifications. Execution (schema, Sheets API connection, build) has not started yet.

Tech (Planned)


Next.js
Google Sheets API
PostgreSQL (planned for later, once Sheets API limits become a bottleneck)



Full Specification

See PlotFlow_CRM_PRD.pdf for the complete product requirements document, including detailed module breakdowns, data structure, and scope boundaries.
[PRD FOR CRM.pdf](https://github.com/user-attachments/files/29576145/PRD.FOR.CRM.pdf)
