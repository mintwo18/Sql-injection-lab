# SQL Injection Security Lab

**Academic group project · Information Security · 2025**

## Overview
A practical university lab exploring SQL Injection (SQLi), its impact on web application authentication and database operations, and basic defensive recommendations.

## My confirmed contribution
- Researched SQL Injection technique categories for the theory and practice section assigned to me.
- Helped design practical attack scenarios.
- Personally performed the practical exercises in all three environments used by the project: Hacksplaining, SQLMap on Kali Linux/VMware, and DVWA on XAMPP.
- Prepared demonstration video material and presented the theoretical component.

This was a five-member group project. This repository describes my confirmed contribution and does not claim sole authorship of the full report or every group deliverable.

## Techniques covered
- In-band SQL Injection: error-based and UNION-based concepts.
- Blind SQL Injection: boolean-based and time-based concepts.
- Out-of-band SQL Injection concepts.
- Login-bypass scenarios caused by unsafe query construction.
- Database enumeration and unauthorized read/write impact.

## Lab environments
| Environment | Purpose |
|---|---|
| Hacksplaining | Interactive SQLi lesson and login-bypass demonstration |
| Kali Linux in VMware | SQLMap practice against a designated vulnerable training target |
| DVWA on XAMPP | Local intentionally vulnerable environment for controlled database exercises |

## Key learning outcomes
1. Observed how unsafe input handling can change SQL query logic and weaken authentication.
2. Practiced using SQLMap to identify SQLi behavior and inspect database structure in a training environment.
3. Used a local DVWA/XAMPP lab to understand SQLi impact on data confidentiality and integrity.
4. Reviewed defenses including parameterized queries / prepared statements, least-privilege database accounts, safe error handling, and authorized security testing.

## Scope and safety
This repository is an educational portfolio summary, not a turnkey exploitation framework. Exercises were performed in designated training or local lab environments. Never test a system without explicit authorization.

## Project materials
- Contribution statement: CONTRIBUTION.md
- Technique and defense notes: TECHNIQUES_AND_DEFENSES.md

The original university report is a group deliverable. Only permission-cleared evidence should be added to this public repository.
