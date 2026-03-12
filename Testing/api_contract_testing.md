# API Postman Collection Generator

## Explanation
Creates a Postman/Newman test collection for an API endpoint.

## Detailed Prompt
Copy and paste the prompt below:

```text
I have the following API endpoint: POST /api/v1/checkout. It requires a JSON body containing 'userId' and 'cartTotal'. Generate a set of Postman test scripts (using the pm.test syntax) to validate: 1. 200 OK for valid requests. 2. 400 Bad Request if 'cartTotal' is negative. 3. Response time is under 500ms. 4. The response JSON schema matches expectations.
```
