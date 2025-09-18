# SparePartsInventoryAssistant

Pseudocode:

- Start program
- prompt: Welcome text
- prompt question: Which part do you need?
- input: part name
- if: part name from input match a part in stock
    - prompt: "I've got this (part name) for you, bye"
    - End program
- if else: input matches two of special queries "Do you actually have any parts?" or "Is there anything in stock at all?"
    - prompt: count and list of parts (in a for loop)
- else: if input not matches any
    - prompt: we don't have it
    - back to prompt question line 7
