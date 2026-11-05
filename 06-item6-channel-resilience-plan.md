# Item 6 – Channel-resilience plan


Collaboration tools, email and the directory may fail or be untrusted during the incident (A4). Slide 10 sets the rule that unconfirmed critical communications are failed communications; this plan therefore pairs every audience with a primary and a fallback channel that run outside corporate infrastructure, a named owner and a confirmation method. Slide 6 and NIST SP 800-61 Rev. 3 both require verified out-of-band channels when identity or collaboration services may be compromised (NIST, 2025).


*Table 9. Channel plan by audience.*


| **Audience** | **Primary channel (out-of-band)** | **Fallback channel** | **Owner (backup)** | **Confirmation method** |
|---|---|---|---|---|
| **Workforce** | SMS from the external bulk provider, using the offline roster and a fixed sender name | Manager phone tree; printed notice at reception and site noticeboards | People Lead (Comms Lead) | Staff reply “1”; target 90% in 60 min. At T+90 min every non-reply gets a personal call, logged by the manager. |
| **Incident command and executives** | Encrypted leadership messaging group and external phone bridge | Direct calls by the Incident Commander to each member | Incident Commander (Comms Lead) | Verbal read-back or written “received” within 15 minutes. |
| **Customers and partners** | Third-party static status page hosted outside corporate infrastructure | Account manager phone calls; support line reading the holding statement | Account Lead (Comms Lead) | Two-way: manager logs each call on an offline sheet; client acknowledgement requested. |
| **Payroll bank** | Call from Finance Lead to the relationship manager, verified by call-back to the number already on file | Bank’s secure portal with separate hardware-token credentials; written confirmation reference | Finance Lead (Director) | Bank confirmation reference recorded in the ledger with time and name. |
| **Regulators and counsel** | Counsel’s secure channel; regulator’s official filing route when Legal decides | Phone to counsel and regulator’s published contact | Legal (Incident Commander) | Counsel’s written acknowledgement; filing receipt. |
| **Media and public** | Reactive line through the Director | Status page entry (same wording) | Director (Comms Lead) | Enquiry log with time stamps. |


*Table 10. Source-of-truth and authenticity controls.*


| **Control** | **How it works** |
|---|---|
| **Independent source of truth** | The ledger and message log are kept on a standalone laptop not joined to the corporate domain, with a printed copy updated hourly. Each entry has a time, owner and status (slide 6). |
| **Message authenticity** | Every message carries the incident reference, the fixed sender name, the Incident Desk number and no links. Staff are told that official messages never ask for credentials or bank details. |
| **Independence test** | Before each send, the sender confirms the channel needs no corporate email, directory, chat or file share. If it does, the fallback is used. |
| **Failed-comms rule** | Any critical message without confirmation at its deadline is treated as not delivered and escalated to the fallback (slide 10). |

---

[⬅ Back to README](../README.md) | [⬅ Previous](05-item5-executive-briefing.md) | [Next ➡](07-item7-rationale-reflection-checklist.md)
