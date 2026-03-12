# Regex ReDoS / Backtracking Fix

## Explanation
Fixes regular expressions that freeze the CPU.

## Detailed Prompt
Copy and paste the prompt below:

```text
This regular expression I am using is causing my server CPU to spike to 100% and hang forever when validating a specific long string: [Paste Regex and String]. Explain why 'Catastrophic Backtracking' or a ReDoS vulnerability is happening here, and rewrite the regex to be completely linear and safe for production.
```
