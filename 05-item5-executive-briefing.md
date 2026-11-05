# Item 5 – Executive briefing


**PRIVILEGED AND CONFIDENTIAL. Prepared at the direction of Legal; Legal to confirm treatment.** For the Director and, through the Director, the Board Chair. Version 1 for the 10:30 Monday call. Next written update 12:30; call 16:30.


**Situation.** The shared file service has been unavailable to several departments since 08:15. Ransomware is suspected but not confirmed. Payroll runs Friday. An unverified screenshot is circulating inside and outside the organisation. The first employee statement was sent at 09:15 as planned.


## Four-quadrant ledger (ICDFA, n.d., slide 6)


*Table 5. Time-stamped as at 10:30 Monday; owner shown for each item still to verify.*


| **Quadrant** | **Content** |
|---|---|
| **Confirmed** [Confirmed] | Several teams cannot access shared files (from 08:15). Security team is preserving evidence and investigating. Payroll processing is scheduled for Friday. A screenshot is circulating internally and externally (its existence only). Staff statement issued 09:15. |
| **Unknown** [Unknown] | Attacker and root cause; entry point; number of affected systems; whether data was accessed or taken; whether payroll data and backups are intact; recovery time; whether regulator notification is required; whether the screenshot is genuine. |
| **Assumed** [Assumption] | Bank cut-off Thursday 15:00 (A2); 24-hour manual payroll fallback (A3); email and chat untrusted (A4); NDPA 72-hour planning clock from Monday 08:15 (A7). |
| **To verify next** | 1) Integrity and age of last clean payroll data: Technical Lead and Finance Lead, 12:00.<br>2) Bank cut-off and manual route: Finance Lead, 11:30.<br>3) Screenshot provenance and content review: Technical Lead, 12:00.<br>4) Backup status: Technical Lead, 12:00.<br>5) Whether personal data is involved: Technical Lead with Legal, not before forensic triage; checked 12:30 and Tuesday 09:00.<br>6) Forensic firm, counsel and insurer engaged: Incident Commander, 11:00. |


## Exposure metrics (assumptions A1–A3, A7)


*Table 6. Fiduciary and time exposure.*


| **Metric** | **Value** | **Meaning** |
|---|---|---|
| **Employees depending on Friday payroll** | 180 | Largest affected population. |
| **Payroll value at risk of delay** | NGN 54,000,000 | One monthly run. |
| **Time from 08:30 Monday to bank cut-off** | 78.5 hours | 3 days 6.5 hours to Thursday 15:00. |
| **Latest start of manual fallback** | Wednesday 15:00 | Thursday 15:00 minus 24 hours. |
| **Decision gates** | Tuesday 12:00 and Wednesday 12:00 | Gate 2 leaves 3 hours before the latest start. |
| **Regulator planning clock** | Thursday 08:15 | 72 hours from Monday 08:15; for planning, not a legal conclusion. |


## Risks


*Table 7. Principal risks and owners.*


| **Risk** | **Rating** | **Response** | **Owner** |
|---|---|---|---|
| Payroll slips past Friday | High | Parallel manual fallback prepared from Monday; gates on Tuesday and Wednesday. | Finance Lead |
| Screenshot fills the information gap or is acted on | High | Employee statement; hourly monitoring; one approved line. | Comms Lead |
| Conflicting statements by several voices | Medium | Director only; all others use the reactive line. | Incident Commander |
| Premature disclosure or exoneration creates legal liability | High | Legal clears every release; no “no evidence of loss” claims. | Legal |
| Fraud and phishing exploiting the incident, especially payroll | Medium | Warnings in staff and client messages; call-back verification for any bank change. | Finance Lead |


## Decisions required


*Table 8. Decisions, deadlines and default if no decision is made.*


| **#** | **Decision** | **Decider** | **By** | **Default if undecided** |
|---|---|---|---|---|
| D1 | Confirm the Director as the only external voice and a freeze on unapproved statements | Director | 10:45 | Freeze continues |
| D2 | Authorise Finance to open the bank contingency conversation and prepare manual payroll in parallel | Director | 10:45 | Prepare only; promise nothing to staff |
| D3 | Engage forensic firm and external counsel, and notify the insurer | Director | 11:00 | Technical Lead keeps preserving evidence |
| D4 | Release the client update (C4) after Legal clearance | Director | 11:30 | Reactive line only |
| D5 | Adopt payroll gates: Tuesday 12:00 review; Wednesday 12:00 invoke fallback if clean data is not verified | Director | 12:30 | Gates apply as shown |
| D6 | Approve Board escalation triggers (Item 1) | Director | 12:30 | Triggers apply as shown |


**Containment risk.** Staff are told not to restart or switch off machines unless instructed, to protect volatile evidence (CISA et al., 2023). The cost is that infected machines may stay connected until the Technical Lead isolates them. **Next update: 12:30 (written), 16:30 (call).**

---

[⬅ Back to README](../README.md) | [⬅ Previous](04-item4-customer-partner-update.md) | [Next ➡](06-item6-channel-resilience-plan.md)
