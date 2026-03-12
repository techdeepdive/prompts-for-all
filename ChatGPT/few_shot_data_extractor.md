# Few-Shot Data Extraction

## Explanation
Trains ChatGPT via examples to format unstructured text into clean JSON.

## Detailed Prompt
Copy and paste the prompt below:

```text
I need to extract data from random text snippets. Here are two examples of what I want:
Input: 'John bought 3 apples for $5.' | Output: {"Name": "John", "Item": "Apple", "Quantity": 3, "Cost": 5.00}
Input: 'Sarah purchased a Tesla Model 3 for $40000.' | Output: {"Name": "Sarah", "Item": "Tesla Model 3", "Quantity": 1, "Cost": 40000.00}
Now, do exactly the same formatting for this input: '[Paste new unstructured text]'. Only output purely formatted JSON.
```
