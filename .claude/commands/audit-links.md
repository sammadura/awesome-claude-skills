---
description: "Audit all links in the awesome-list for validity and accuracy."
---

# Audit Links

Check all links in README.md for validity.

## Process

1. Extract all URLs from README.md
2. For each link, verify it's reachable and points to the expected content
3. Flag any:
   - Broken links (404, connection errors)
   - Redirected links (update to final URL)
   - Archived/deprecated repositories
   - Links pointing to unexpected content

## Reporting

For each issue found, report:
- The link text and URL
- The problem (broken, redirected, archived, etc.)
- Suggested fix (remove, update URL, add note)

## Note
Some links may be rate-limited. If a link check fails, retry once before flagging it.
