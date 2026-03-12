# XML Enforced Formatting

## Explanation
Claude excels at outputting and following XML tags. Use this to heavily constrain output format.

## Detailed Prompt
Copy and paste the prompt below:

```text
Analyze the provided text. You must output your analysis strictly within the following XML tags: <summary> for a 2-sentence summary, <key_entities> for a comma-separated list of people/places, and <sentiment_score> for a number between 1 and 10. Do not include any text outside of these XML tags. Here is the text: [Paste text].
```
