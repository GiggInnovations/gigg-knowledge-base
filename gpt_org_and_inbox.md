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

  # Switching Between Organizations

Users who belong to multiple organizations can easily switch their working context.

## Steps to Switch Orgs
![Switching Between Orgs](https://github.com/user-attachments/assets/a6c64ed5-5361-4225-8735-96e8b5390346)

1. **Click the User Icon**  
   - Located in the bottom left corner of the screen  
   - Icon resembles a head and upper body silhouette

2. **Select "Switch Orgs"**  
   - This is the first option in the popup menu

3. **Choose an Organization**  
   - A modal will display all orgs the user belongs to  
   - Use the scroll feature to browse all available orgs  
   - Use the search bar at the top of the modal to quickly find a specific org  
   - Selecting an organization switches context immediately—no confirmation required

## Additional Notes

- **Default Org on Sign-In**: When signing out and back in, users are automatically placed in the first org listed alphabetically.
- **Current Org Indicator**: The user’s name and current org name are shown to the right of the User icon in the bottom left corner.

---

This reference can be reused for future documentation or onboarding.
