# Comment Competition and Post competition setup
How comment and post competitions are setup in **Challenge Settings > Setup**

## Comment Competitions
The admin chooses an Instagram or X post for the participants to comment on. Once the competition has begun, any comments on the post will appear in the inbox. These are the entries for the competition. The admin can decide if the winner is chosen either by random or by the company's choice.

### Type

- Select **Comment Competition** from the Challenge Submission Type dropdown  
![image](https://github.com/user-attachments/assets/b21e5396-9cbb-4aae-9c25-7207d3f7fb5f)

- Enter an Admin Phone number. This will be the number that receives messages related to the competition.  
![Screenshot 2025-08-12 6 04 03 PM](https://github.com/user-attachments/assets/4cf18475-4cab-4c40-bdc4-e6e3829cc40d)

- Select one or more categories from the **Challenge Categories** dropdown.  
![Screenshot 2025-08-12 6 05 55 PM](https://github.com/user-attachments/assets/f4d36a52-065a-4278-805b-68d0fda8e2cd)

### Rounds
Function the exact same as the rounds of a site competition. The only difference is there are only two choices for how winners are chosen. These are **Random** and **Company Choice**. There is no voting for comment competitions or post competitions.

### Social

1. Connect an Instagram, X, and/or Circle account  
![image](https://github.com/user-attachments/assets/be6036c8-3bb3-459d-9cac-cebfb4a5e1b5)

2. Select a post from the connected Instagram or X account. This is the post that participants will comment on.  
![image](https://github.com/user-attachments/assets/c5034b55-3eb2-418e-8f21-c4a63d51fdfd)

- Connecting a Circle account will allow submissions to be uploaded to Circle.

### Terms and Conditions
Functions the exact same as in the Site Competitions.

### Finalize
Functions the exact same as in the Site Competitions.

### Some tips from Gigg

This is not a tab in the setup phase, just some tips for setting up a successful comment competition

To set up, the following is needed from the clients:
- Prize secured
  - Verify who is responsible for payment and distribution of the prize.
- Social Media accounts connected to Gigg software.
- Reel or graphic for post created with caption explaining the giveaway.
  - Format for Post/Reel:
    - Welcome/Introduction
    - Prize Tease (We’re giving away ……..)
    - How to win? “Make sure you’re following………….. Tag your friends below. More Tags = More Entries Prize explanation. We’ll randomly select ____ winners.
    - Close with when it ends, etc. 
  - Tips
    - Reels are better than posts because it reaches a larger audience.
    - If using an influencer, consider having them record the reel and posting it on their page with the client collaborating on the post.
    - Share the post to your story.
    - Pin the post so it appears at the top of your feed. 
- Chatfuel setup and connected to client social accounts. 
    - Automation → Flows → Comments Automated
    - Select the post you want to apply the bot to → Select “Reply to all Comments”
    - (New Box) REPLY: Public Reply → Delay 5 minutes
      - Add multiple text options for what the replies will say 
      - Select “Private Reply” → Delay 30 seconds 
      - Type Text
        - Thank them for entering.
        - Tease offer and ask for email
      - Collect Answers
    - (New Box) Delay 30 seconds
    - (New Box) Send Message
      - Type the response with the code/offer
      - Tease the next competition 
        - Tip: It is helpful to sound more casual/conversational in this response.
    - (New Box) Send Data to Google Sheet

---

## Post Competitions
All X and Instagram posts that tag the account connected in the **Social** tab will be pulled into the competition. These are the competition entries. The admin can decide if the winner is chosen either by random or by the company's choice.

### Type

Exact same as comment competitions except with the extra UI of **Recurring Schedule**

- Recurring schedule: A toggle (default off) that allows the post competition to be repeated either weekly or monthly. This is determined by a dropdown where the admin can choose "weekly" or "monthly".  
![Screenshot 2025-08-12 6 38 30 PM](https://github.com/user-attachments/assets/dd460ff8-6c15-4982-963d-255c20560925)

### Rounds

Functions the exact same as a Comment Competition

### Social

Connect an Instagram, X, and/or Circle account.  
![image](https://github.com/user-attachments/assets/16a1a128-8ea1-4b80-a68e-33aa77e83b80)

### Terms and Conditions
Functions the exact same as in the Site Competitions.

### Finalize
Functions the exact same as in the Site Competitions.
