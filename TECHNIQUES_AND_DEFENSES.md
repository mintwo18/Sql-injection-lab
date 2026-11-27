# SQL Injection: Techniques and Defensive Notes

## Technique families covered by the coursework

| Family | Variants / concept |
|---|---|
| In-band SQLi | Error-based and UNION-based |
| Blind SQLi | Boolean-based and time-based |
| Out-of-band SQLi | Indirect exfiltration through a separate channel |

The group work also discussed login bypass, database enumeration, and the potential impact of unauthorized data insertion, modification, and deletion.

## Defensive recommendations reviewed
- Use parameterized queries / prepared statements so data is separated from SQL syntax.
- Apply least-privilege permissions to database accounts.
- Avoid exposing detailed database errors to end users.
- Treat input validation as defense in depth; do not rely on filtering alone.
- Perform security testing only in approved environments and within an explicitly authorized scope.

## Lab boundary
The practical activities used interactive training content, a designated vulnerable training website, and a local DVWA/XAMPP lab. This document intentionally avoids publishing a reusable attack script or encouraging tests against real systems.
