---
audience: internal
tags: [inbox, backend, filtering, support]
---

# Inbox: Internal Behavior and Notes

This file provides backend notes and support-facing guidance for how the Social Inbox works within Gigg.

## Default Behaviors

- Inbox opens to **unpinned + newest** posts by default
- Keyword filtering only affects social posts — not RSS
- RSS posts are always pulled in full and are visually labeled differently
- Inbox auto-refreshes periodically with new content

## Blocking Logic

- When a user blocks a social media account, posts from that user are immediately hidden, even pinned posts
- To unblock: go to `Inbox Settings > Inbox > Blocked Social Accounts`
- Posts from a previously blocked user will not reappear until:
  - The relevant keyword is removed and re-added

## Post Interaction Logic

- Pinned posts disappear from the unpinned view but remain in the board(s)
- Users can **unpin posts directly from a board view**
- If no custom board exists, pinned posts default to a board called **"Pinned"**
- This default board behaves the same as other boards (not locked or restricted)

## Search + Filter Implementation

- Search bar filters by:
  - Keyword (exact match)
  - Platform (dropdown-generated)
  - Post content (free text)
- Error message displays:
  - `"We couldn't find any posts for your keywords"` when no matches exist
  - Same message appears if RSS feed returns no posts
  - Broken RSS feeds are silently logged but skipped

## Known Limitations

- Posts can’t be edited within the inbox
- No admin notification system exists for new inbox activity
- No "undo" for deletes or blocks
