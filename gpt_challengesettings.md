---
audience: user
tags: [competition, challenge settings, general]
---

# Challenge Settings

## Challenge Settings > General

This section controls core details, sharing options, and high-level actions for your competition.

---

### Competition Info

- **Competition Name**: Editable text box for renaming the competition.
- Changes are saved instantly when you click outside the field.

---

### Share Messaging

- **Share Post Title**: Text displayed on social media posts when a user shares content from your competition.
- Example: *"Check out this cool post"*
- Default is blank; enter your desired message in the provided text box.

---

### Facebook Pixel

- **Facebook Pixel ID**: Enter your Pixel ID in the provided text box to help track visitors and run targeted ads.

---

### Share to Circle

- **Circle Community Link**: Auto-generated URL for sharing the competition in a Circle Community.
- Click to copy, then paste into Circle to redirect users to the competition.

---

### Duplicate Competition

- Click **Duplicate Competition** to create a copy with the name format:  
  `{Competition name} Copy`
- **What’s copied**:
  - All competition settings
- **What’s not copied**:
  - Any entries
- After duplication:
  1. The message *"Challenge duplicated! Check it out **here.**"* appears.
  2. Click **here** to open the duplicate.
  3. Accept terms & conditions before publishing.

---

### Export Challenge Entries to Inbox

- Click **Export Competition** to create a social inbox containing competition entries as posts.
- This inbox can be displayed on a site or screen.

---

### Cover Image

- Used only inside the Gigg UI (not on the public board).
- Upload by:
  - Drag-and-drop into the image area, or
  - Click to open a file browser and select an image.

---

### Delete Competition

- Click **Delete This Competition** to open the deletion modal.
- Type `delete` in the modal text box to enable the **Delete Competition** button.
- Once confirmed, deletion is permanent and cannot be undone.

---

## Competition Settings > Users

Manage who can access and contribute to your competition. Users can be invited, assigned roles, or removed.

---

### Invite a User

1. **Click the Invite Button**  
   - Icon: User silhouette with a **"+"** symbol.
   - Opens an invitation modal.
     ![Open user invite](https://github.com/user-attachments/assets/902e3de3-a053-446a-9b4b-2737b2420420)


2. **Enter User Email**  
   - Type the email address into the **User** text box.
     <img width="926" height="392" alt="image" src="https://github.com/user-attachments/assets/dfa7f5e9-3cd0-4543-9bfd-712e2859115a" />

3. **Assign Role**  
   - Click the **Role** dropdown and choose:
     <img width="926" height="392" alt="image" src="https://github.com/user-attachments/assets/487c78be-98c5-4076-b961-7af34263fd57" />

     - **Admin**
     - **Member**
     - **Viewer**

4. **Invite Multiple Users**  
   - Click **+ Invite another user** to add more rows.
   - Repeat the email and role selection steps.
     ![Invite Multiple Users](https://github.com/user-attachments/assets/31d3f6a2-e5a9-41f2-89f2-ee0e8eaa6e89)


5. **Send Invitations**  
   - Click **Invite** to send email invitations to all listed users.
     ![Send Invite](https://github.com/user-attachments/assets/84825dab-74fc-41bd-899b-865739044263)

   - **If already in the org**: User is added instantly.
   - **If not in the org**: User must accept via email invite before gaining access.
   - Pending invites appear in the **Pending** section until accepted.
     <img width="1605" height="601" alt="image" src="https://github.com/user-attachments/assets/cf0d859f-6c53-4801-a1ae-aaff44760f94" />

   - Accepted invites appear in the **Active** section.
     <img width="1605" height="612" alt="image" src="https://github.com/user-attachments/assets/4cd6eea2-a701-4317-8067-3523a570ac71" />


---

### User Roles & Permissions

Competition users are divided into three groups.  
All roles can view the **admin side** of the competition.

#### **Admin**
- Full access to Inbox and Board settings.
- Can:
  - Moderate Inbox and Board content.
  - Add/update keywords.
  - Invite/manage other users.
  - Change user permissions.
  - Unblock social accounts.

#### **Member**
- Can:
  - Moderate the Social Inbox.
  - Create and publish Boards.
  - Pin posts.
  - Display Boards in different formats.
- **Cannot** access Inbox settings.

#### **Viewer**
- Can:
  - Display any published Boards (on display or embedded on web).
- **Cannot**:
  - Access Social Inbox.
  - View Pinned or All Posts.
  - Access Inbox settings.

---

### Remove a User

- Each user has a **Remove** button (user silhouette with a **"-"** symbol).
- Clicking opens a confirmation modal.
- Click **Remove** to revoke access.
  ![Remove user](https://github.com/user-attachments/assets/aa879686-3e46-4d49-842c-2872c2623fd5)

---

## Display Options

Control the visual style and branding for your competition.

---

### Color Settings

- **Primary Color**:  
  - Select from a color palette.  
  - Used for buttons and some links throughout the competition UI.  
  - Best practice: match your brand’s primary color.

- **Light Theme**:  
  - Toggle to enable a lighter version of the Challenge UI.

- **Hide Gigg Logo**:  
  - Toggle to remove the Gigg logo from the competition display.

---

### Logo

- Upload a logo to be shown in all competition-related emails.
- Methods:
  - Drag-and-drop the image into the upload area.
  - Click the upload area to select a file from your computer.
- Ensure the logo is clear and sized appropriately for email layouts.

---

### Custom CSS Override

- Add custom CSS rules to override default Challenge styles.
- All elements in your Challenge use HTML classes prefixed with `public__`.
- Add your CSS code directly in the **CSS Override** field.

---

## Reports

- Exports are available for
  - Voters
  - Stats
  - Entrants
  - Referrals
