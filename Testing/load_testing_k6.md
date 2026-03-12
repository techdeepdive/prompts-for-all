# K6 Load Testing Script

## Explanation
Writes a script to simulate heavy traffic on a server.

## Detailed Prompt
Copy and paste the prompt below:

```text
Write a performance testing script using k6 (in JavaScript) to load test this endpoint: [URL]. The test should ramp up to 100 Virtual Users (VUs) over 30 seconds, hold for 1 minute, and ramp down over 30 seconds. Assert that 95% of requests complete in under 200ms and the error rate is less than 1%.
```
