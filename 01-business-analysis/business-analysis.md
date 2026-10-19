\# System Notification Management – Business Analysis



\*\*Version:\*\* 1.0 | \*\*Date:\*\* 2026-10-19



\## 1. Purpose and Background

Provide a centralized notification platform for sending business transaction notifications through Email, SMS, and WhatsApp, replacing ad hoc, per-module messaging.



\## 2. Scope

\- Notification templates and channel configuration

\- Auto / Prompt / Manual sending

\- Email attachments (voucher and additional)

\- SMS dashboards (Super Admin and Client)

\- Notification history and status tracking





\## 3. Channels

| Channel | Summary |

|---|---|

| Email | Template-based; voucher and additional attachments; delivery tracking |

| SMS | Providers Sparrow and QuickConnect; templates; usage and delivery tracking |

| WhatsApp | Template messaging with variable replacement; delivery tracking |



\## 4. Supported Modules

Sales Invoice, Sales Return, Purchase Invoice, Purchase Return, Credit Note, Debit Note, Cash/Bank Voucher, Journal Voucher.



\## 5. Send Modes

| Mode | How it works |

|---|---|

| Auto | Sent in the background right after voucher save, with no user action |

| Prompt | A popup appears after save; the user picks a template, edits content, and sends |

| Manual | The user starts from a listing page, picks a template, edits content, and sends |



\## 6. Actors and Roles

| Actor | Role |

|---|---|

| Super Admin | Views license-wise SMS usage across all clients |

| Client Admin | Configures templates and channels; views own SMS dashboard |

| User | Saves vouchers; sends notifications in Prompt and Manual modes |

| System | Sends Auto notifications and records status |



\## 7. Dashboard Overview

\- \*\*Super Admin (license-wise):\*\* SMS per client/license, usage by provider, daily/monthly consumption, remaining balance, success/failed statistics.

\- \*\*Client:\*\* total sent, by module, by provider, monthly trend, success/failed statistics, balance and utilization.



