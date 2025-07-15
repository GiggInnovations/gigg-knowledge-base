---
audience: internal
tags: [competition, setup, admin, configuration]
---

# How admins setup a site competition

- Find the setup options in Challenge Settings > Setup > Type. The "Challenge Submission Type" dropdown will have "Post Competition" selected by default. Click the dropdown and choose "Site Competition". Enter the required information ("Challenge Categories" and "Admin Phone Number") and click the Save button in the bottom right. This will cause all the setup tabs for a site competition to appear.
- Fields shared between Post and Site Competitions will retain their values when switching types.

## Setup options in the "Type" tab:
1. Text/Dropdown: Challenge Embed URL (required), Accepted Submission Media Types (enforces upload restrictions), Media Limit per Submission (UI blocks exceeding uploads)
2. Toggles: Hide Vote Count, Single Vote per User, Enable Anonymous Voting, Voters Subscribed by Default
3. Media Uploads: Intro Video, Intro Image or Thumbnail, Confirmation Video, Background Image, Prize Video, Prize Image or Thumbnail

## Using the "Rounds" tab:
1. Choose start/end times (start must be in future, end at least 15 min later)
2. Add/Edit Rounds with "Add Round" button. For each round:
   - Rename, set dates
   - Choose winner selection method and count
   - Toggle Auto-Notify Competitors and Auto-Advance Rounds
3. If Auto-Advance is off, the admin must click "Advance Round" manually.
   - When a round ends with no action, competition pauses. A message appears on the site stating that the next round will begin shortly.
4. Press "Save Rounds" in the bottom right

## Using the "Submissions" tab:
1. Add an optional redirect URL after submission
2. Toggle visibility/requirement for: Name, Phone, Email, Caption, Country, State, City
   - At least one must be required, and a field must be visible to be required
   - These toggles apply globally across competitions
   - Admins cannot add custom fields
3. Press "Save" to apply changes

## Using the "Rules" tab:
1. Edit default Challenge Introduction/Description
2. Challenge Rules is required to publish and starts blank

## Using the "Messaging" tab:
1. Default messages populate upon selecting Site Competition
2. Message types include:
   - Submissions Email, Advancement Email, Advancement SMS, Condolences Email, Condolences SMS, Final Email, Winner Email, Winner SMS
3. Optional fields: Voting Stage Subtitle and Submission Instructions
4. Variables (e.g., `{submission_name}`, `{round_number}`) can be used in templates

## Using the "Terms & Conditions" tab:
1. Displays Gigg terms (not editable)
2. Must click "Accept" to proceed

## Using the "Finalize" tab:
1. Shows a checklist summary of all tabs
   - Tabs with missing required fields are outlined in red
2. No draft or preview mode exists
3. Once complete, the "Publish" button becomes clickable and publishes to the Gigg Competitions website
