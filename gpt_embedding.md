---
audience: user
tags: [embedding, boards, public submissions, iframe]
---

# Embedding Boards and Public Submission Forms

Boards and Public Submission forms can be embedded into websites using iframe code generated inside Gigg.

---

## Embedding a Board

1. Navigate to the board you want to embed through the **Boards** dropdown on the left of the screen.                                                       ![Boards dropdown](https://github.com/user-attachments/assets/e67ce9fc-2e36-401b-991f-d414b59c9af1)

2. Click the 3 vertical dots menu button at the top right of the screen.                                                                                     ![Board Menu Button](https://github.com/user-attachments/assets/fe4f0af0-d029-4386-9394-c02e24d50736)

3. Make sure the board is Published. 
4. Click **Display Board**.
5. Choose the desired **Display Type**:
   - Standard
   - Masonry
   - Carousel
6. Click the `</>` icon to copy the embed code.  
   ![Copy Embed code button](https://github.com/user-attachments/assets/ee7d418f-1490-4192-ab12-69aee3df7dfa)



7. Paste the embed code into your site’s HTML where you want the board to appear.

---

## Embedding a Public Submission Form

1. Go to `Inbox Settings > Public Submission`.
2. Customize the form fields, header, description, and terms.
3. Click the **Copy Embed Code** button to copy the embed iframe code.  
   ![Public submission form embed button](https://github.com/user-attachments/assets/2d1fc2bf-af97-4b55-94ab-71cbb6add654)


---

## Competitions
- After clicking **Publish** in the finalize tab, a modal appears.  There is a button for **Copy Embed Code**. 
  ![Embed Button for Site competitions](https://github.com/user-attachments/assets/da9e5713-1222-4528-95f2-2699a2b1101b)
- This allows the competition/voting iframe to be embedded into the user's website
  ![Embedded iframe](https://github.com/user-attachments/assets/3d56882c-1e3c-4b89-ac15-b185f9c3a99d)

---
  
## Embed Code Example

```html
<iframe src="https://embed.gigg.com/board/example" width="100%" height="800" style="border:none;"></iframe>
