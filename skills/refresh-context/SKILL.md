---
name: refresh-context
description: >
  This skill should be used when the user says "refresh my context", "reload my context doc",
  "re-read my context", "update context", or "load my background".
metadata:
  version: "0.1.0"
---

# Refresh: Personal Context Document

1. Search ~~google drive for a Google Doc with "Claude Context" in the name.
2. Fetch the full contents.
3. Absorb as the new background context for the rest of the session.
4. Confirm with: "Got it — context reloaded."

If not found, tell the user and offer to run setup-context.
