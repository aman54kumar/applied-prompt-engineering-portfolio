## Prompt Version 1 – Baseline

### Prompt
Analyze the following tender document and summarize it.

### Observed Output Issues
- Output is too generic
- Important requirements are missing
- Structure varies between runs
- No clear separation of scope, deliverables, or risks


## Prompt Version 2 – Structured Tasks

### Prompt
You are an enterprise solution analyst.

Analyze the following tender document and perform the following:
1. Identify scope of work
2. List expected deliverables
3. Highlight potential risks or constraints

Provide the output under clearly labeled sections.

### Improvements Observed
- Better separation of information
- More relevant details extracted
- Still includes assumptions in some areas
- Tone varies and may not be government-appropriate


## Prompt Version 3 – Controlled Output

### Prompt
You are an enterprise tender response consultant.

Analyze the tender document strictly based on the provided text.
Do not assume or infer information that is not explicitly stated.

Tasks:
1. Summarize scope of work
2. Extract deliverables
3. Identify risks or compliance requirements

Rules:
- If information is missing, state "Not specified in the document"
- Use formal, neutral language
- Present output in a structured format

### Improvements Observed
- Reduced assumptions
- More consistent structure
- Suitable for professional review
