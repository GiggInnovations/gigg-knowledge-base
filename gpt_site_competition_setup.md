---
audience: internal
tags: [competition, setup, admin, configuration]
---

# How admins setup a site competition

- Find the setup options in Challenge Settings > Setup > Type. The "Challenge Submission Type" dropdown will have "Post Competition" selected by default. Click the dropdown and choose "Site Competition". Enter the required information ("Challenge Categories" and "Admin Phone Number") and click the Save button in the bottom right. This will cause all the setup tabs for a site competition to appear.
  ![site competition tabs appear](https://github.com/user-attachments/assets/322f4832-ddbb-4859-b59c-70a4bb7ffa83)

- Fields shared between Post and Site Competitions will retain their values when switching types.

## Setup options in the "Type" tab:
1. Text/Dropdown: Challenge Embed URL (required), Accepted Submission Media Types (enforces upload restrictions), Media Limit per Submission (UI blocks exceeding uploads)
2. Toggles: Hide Vote Count, Single Vote per User, Enable Anonymous Voting, Voters Subscribed by Default
<img width="1581" height="536" alt="Screenshot 2025-07-29 9 07 48 AM" src="https://github.com/user-attachments/assets/358ffc1b-f208-47f6-bc41-8439e2cb437c" />


3. Media Uploads: Intro Video, Intro Image or Thumbnail, Confirmation Video, Background Image, Prize Video, Prize Image or Thumbnail
   <img width="1629" height="821" alt="image" src="https://github.com/user-attachments/assets/c27880af-be95-4358-85c4-a5a2ba93ffc9" />


## Using the "Rounds" tab:
1. Choose start/end times (start must be in future, end at least 15 min later)
   <img width="1629" height="821" alt="image" src="https://github.com/user-attachments/assets/31e1834a-1093-412a-868b-5aeb3733b283" />
3. Add/Edit Rounds with "Add Round" button. For each round:
   - Rename, set dates
   - Choose winner selection method and count
   - Toggle Auto-Notify Competitors and Auto-Advance Rounds
   <img width="1629" height="466" alt="image" src="https://github.com/user-attachments/assets/0fdb0ba0-bf83-4b48-842c-8cc89eded026" />


4. If Auto-Advance is off, the admin must click "Advance Round" manually.
   - When a round ends with no action, competition pauses. A message appears on the site stating that the next round will begin shortly.
5. Press "Save Rounds" in the bottom right

## Using the "Submissions" tab:
1. Add an optional redirect URL after submission
2. Toggle visibility/requirement for: Name, Phone, Email, Caption, Country, State, City
   - At least one must be required, and a field must be visible to be required
   - These toggles apply globally across competitions
   - Admins cannot add custom fields
3. Press "Save" to apply changes
   <img width="1606" height="828" alt="image" src="https://github.com/user-attachments/assets/56e02d61-ddec-4eed-aa62-8491a7d576bd" />


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
     <img width="1606" height="793" alt="image" src="https://github.com/user-attachments/assets/2c76578b-1b4d-44af-8503-9be9249ca786" />
3. No draft or preview mode exists
4. Once complete, the "Publish" button becomes clickable and publishes to the Gigg Competitions website ![successful_publish_challenge](https://github.com/user-attachments/assets/3eb3895a-17cb-4611-9743-590c96c8730c)
   

