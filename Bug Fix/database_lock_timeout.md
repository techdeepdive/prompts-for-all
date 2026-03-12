# Database Deadlock & Timeout Fix

## Explanation
Diagnoses locking issues when multiple queries hit a row simultaneously.

## Detailed Prompt
Copy and paste the prompt below:

```text
My application occasionally throws a 'Transaction deadlock' or 'Row lock timeout' error on my [MySQL/PostgreSQL] database during heavy concurrent writes. Here are the two queries that are running: [Paste Queries]. Explain why they are deadlocking, and suggest a solution (e.g., ordering structural updates, changing isolation levels, or retries).
```
