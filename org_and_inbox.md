# Platform Structure & Permissions Reference

This document summarizes key platform structures and internalized context regarding user roles, org relationships, and functional boundaries.

## Organization vs. Inbox

### Organization (Org)
Top-level entity containing users, inboxes, boards, and competitions.

- Controls access to settings, analytics, and user permissions
- Users can switch between orgs if they're part of more than one

### Inbox
Workspace within an org used to pull and manage social and RSS content.

- Filters content based on keywords
- Content is used for pinning to boards and analytics

## Competitions

- Competitions are scoped to the organization they are created in
- Only Org Admins or authorized users within the org can configure or manage them
- Submissions, voting, and messaging all flow through the org’s infrastructure

## User Roles

### Organization Roles

#### Org Admin
- Full access to all org-level settings and content
- Can:
  - Add/edit feeds, keywords, boards
  - Invite/remove users
  - Assign/reassign user roles

#### Org Member
- Limited to assigned boards
- Can:
  - View boards and analytics
  - Pin/delete posts
  - Block users
- Cannot:
  - Edit inbox settings
  - Manage user access or org connections

### Board Roles

#### Board Admin
- Can manage inbox settings and invite members (as any role)
- Cannot remove other admins or change existing member roles

#### Board Member
- Can:
  - View inbox, boards, and analytics
  - Pin/delete posts
  - Create new boards within the inbox

#### Board Viewer
- Read-only access
- Can view inbox and boards but cannot modify or create content

---

This reference can be reused for future documentation or onboarding.
