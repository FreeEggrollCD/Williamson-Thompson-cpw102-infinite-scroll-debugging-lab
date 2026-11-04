# Incident Note — INC-204

**Responders:**

## Investigation log

Record **every debugging step in chronological order as you work**, including unsuccessful attempts and changes you undo. Commit your work as you go. 

For each step, briefly note what you tried and why, what you observed, and what you concluded or decided to try next.

Include relevant inputs, code changes, or output so someone else can follow your investigation. 

Use numbered entries or timestamps. Use Markdown formatting to make it easy to read.

1. Entering 'y' adds the same 3 feeds to the next list of feed.
2. Old feeds aren't removed.
3. Looks like it only checks for a 'n' input to end the loop.
4. Improper input sanitization.

## Resolution

Explain the causes, your repairs, and the evidence that verifies them. Identify
anything still uncertain or unresolved. Make code changes in `feed.py`.
