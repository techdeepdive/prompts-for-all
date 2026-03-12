# Async Race Condition Debugger

## Explanation
Identifies asynchronous promise or threading bugs that happen randomly.

## Detailed Prompt
Copy and paste the prompt below:

```text
I have a bug in my [JavaScript/Python/Go] code that only happens 20% of the time, leading me to believe it's a race condition or async await issue. Code: [Paste Code]. Analyze the concurrency model. Point out exactly where an unhandled promise, missing await, or thread lock issue is allowing out-of-order execution, and fix it.
```
