# Sona Khata

**AI-Powered Gold Accounting & Trust Management Platform**

Theme: Jeweltech · Problem Statement 2.2: Gold given to karigars for job-work is tracked on trust, and disputes follow.

## Problem
Jewellers give gold to karigars for job-work, but these deals are usually tracked on trust. This leads to:
- No proper records of gold transactions
- Disputes over gold weight and wastage
- Delayed jewellery deliveries and labour payments
- No reliable work history for karigars to show new jewellers

## Solution
A shared digital gold ledger where both the jeweller and the karigar can see, check and approve every transaction.

## How It Works
| Step | What happens | AI Agent |
|---|---|---|
| 1. Gold Entry | Jeweller sends a WhatsApp voice message; AI turns it into a record; karigar confirms | Intake Agent |
| 2. Deadline Tracking | Tracks delivery dates, sends reminders and delay alerts | Deadline Agent |
| 3. Reconciliation | Compares gold given vs returned, wastage and scraps; flags differences | Reconciliation Agent |
| 4. Settlement | Calculates labour charges and balances; both parties approve the statement | Settlement Agent |
| 5. Trust Profile | Tracks completed orders and on-time deliveries; shareable profile | Trust Score Agent |

## Smart Gold Weighing (Hardware)
Digital scale → ESP32 microcontroller → app records the weight automatically → both parties see the same reading.

## Tamper-Evident Records
- Every transaction gets a unique hash
- Each record is linked to the previous one
- Unauthorized changes can be detected
- Approvals from both parties are stored

## Business Model
- Karigars: free
- Jewellers: monthly subscription
- Future: partnerships with gold refiners and financial institutions

## Development Plan
1. **Basic Prototype**: accounts, gold transactions, confirmation, return, reconciliation, settlement
2. **AI Integration**: voice recognition, five AI agents, reminders, unusual wastage detection
3. **Hardware Integration**: digital scale + ESP32, automatic weight capture
4. **Final Application**: jeweller and karigar dashboards, trust profiles, full testing

## Presentation
See `Sona_Khata.pdf` in this repository.
