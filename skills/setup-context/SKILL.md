---
name: setup-context
description: >
  This skill should be used when the user says "set up my context", "create my context doc",
  "help me write my Claude context", "set up personal context", "what should I put in my context doc",
  or wants to create or update a personal background document for Claude to reference.
metadata:
  version: "0.1.0"
---

# Setup: Personal Context Document

Guide the user through creating a well-structured personal context document in ~~google drive that Claude will automatically load at the start of every session.

Walk through each section one at a time: Who I Am, How I Communicate, Output Standards, Domain Context, Personal Context, and What I Don't Want. Keep it conversational.

After gathering all sections, create a Google Doc in ~~google drive titled "Claude Context — [User Name]" and confirm success.
