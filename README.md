# SparePartsInventoryAssistant

Pseudocode:

- Start program
- prompt: Welcome text
- prompt question: Which part do you need?
- input: part name
- if input matches part name in array then:
    - prompt: "I've got this (part name) for you, bye"
    - End program
- if input matches one of two special queries then:
    - prompt: count and list all parts
- else if input not matches anything stored then:
    - prompt: we don't have it
    - back to prompt question line 7
