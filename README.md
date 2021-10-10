# Specification of the Overkill.chat

Version 1.0.0

## Brief

A platform where users can write posts, comment on each other posts, create their own groups, join other users' groups, have discussions in the groups they are in, have a 1-on-1 chat with other users, chatting with other group members via a group chat room. The platform also has moderators to moderate the overall platform.

---

## 1. Requirements

### 1. Logged-in User

**1.1. General**  
1.1.1. A **Logged-in User** can create **Group**s.  
1.1.2. A **Logged-in User** can join **Group**s.  
1.1.3. A **Logged-in User** can write, read, update, and delete their own **Post**s.  
1.1.4. A **Logged-in User** can read other **Logged-in User**s' **Post**s.  
1.1.5. A **Logged-in User** can be banned from the **Group**s they have joined.  
1.1.6. A **Logged-in User** can receive an invitation to be a **Group Moderator** from another **Group Moderator** of a **Group** they haven't joined.  
1.1.7. A **Logged-in User** can write, read, edit, and delete their own **Comment**s in both their own **Post**s and other **Logged-in User**s' **Post**s.  
1.1.8. A **Logged-in User** can initiate one-on-one **Chat Room** with another **Logged-in User**.  
1.1.9. A **Logged-in User** can upvote or downvote a **Post**.  
1.1.10. A **Logged-in User** can upvote or downvote a **Comment**.  
1.1.11. A **Logged-in User** can see a list of **Group Member**s of a **Group**.  
1.1.12. A **Logged-in User** with unverified email posseses the same privileges as a **Public User** until they verify their email.  
1.1.13. A **Logged-in User** can see the total number of **Group Member**s of a **Group**.  
1.1.14. A **Logged-in User** can see a list of **Group Moderator**s of a **Group**.  
1.1.15. A **Logged-in User** can report a **Post**, a **Comment**, and/or a **Group** as inappropriate to the **Platform Moderator** by creating a **Content Report**.  
1.1.16. A **Logged-in User** can see a list of all the **Post**s and **Comment**s they have voted.  
1.1.17. A **Logged-in User** can see a list of the **Post**s they have read.  
1.1.18. A **Logged-in User** must not be able to see who have voted to their **Post**s and **Comment**s.  
1.1.19. A **Logged-in User** can be notified when someone has voted to their **Post**s and **Comment**s.  
1.1.20. A **Logged-in User** can see a list of all **Post**s from all **Group**s they have joined ordered by published time from the newest to the oldest on their **Post**s feed.

**1.2. Saved posts/comments**  
1.2.1. A **Logged-in User** can save a **Post** or a **Comment**.  
1.2.2. A **Logged-in User** can see a list of their saved **Post**s and **Comments**.  
1.2.3. A **Logged-in User** can unsave the saved **Post**s and **Comment**s.

### 2. Group

**2.1. General**  
2.1.1. A **Group** must have at least 1 **Group Moderator**.  
2.1.2. A **Group** must have at least 1 **Group Member**.  
2.1.3. A **Group** can have **Post**s written by its members.
2.1.4. A **Group** must have one and only one **Group Chat Room**.

**2.2. Group Moderator**  
2.2.1. A **Group Moderator** is a **Group Member** who has higher privilege than other **Group Member**s to moderate their **Group**.  
2.2.2. The **Logged-in User** who created the **Group** is the **Group Moderator** by default.  
2.2.3. A **Group Moderator** can invite **Group Member**s to become **Group Moderator**s.
2.2.4. A **Group Moderator** can ban **Group Member**s from the **Group** they moderates.
2.2.5. A **Group Moderator** can see a list of all **Content Report**s of a **Post** or a **Comment** in the **Group** they moderate.  
2.2.6. A **Group Moderator** can see a list of all **Content Report**s of all **Post**s and **Comment**s in the **Group** they moderate.
2.2.7 A **Group Moderator** can hide a **Post** or a **Comment** in the **Group** they moderate, reported by **Group Member**s as inappropriate.

**2.3. Group Member**  
2.3.1. A **Group Member** is a **Logged-in User** who has joined or created the **Group**.  
2.3.2. A **Group Member** can become a **Group Moderator** by accepting the invitation received from the existing **Group Moderator**.  
2.3.3. A **Group Member** can write, read, edit, and delete their own **Post**s in their **Group**.  
2.3.4. A **Group Member** can read other **Group Member**s' **Post**s.  
2.3.5. A **Group Member** can write, read, update, and delete their own **Comment**s in both their own **Post**s and other **Group Member**s' **Post**s in the **Group** they are in.  
2.3.5. A **Group Member** can either accept or deny the invitaion to be a **Group Moderator** received from the another **Group Moderator**.  
2.3.6. A **Group Member** is not considered to be a **Group Member** anymore if they are banned from the **Group** they are in by the **Group Moderator**.  
2.3.7. A **Group Member** can report a **Post** or a **Comment** in the **Group** they are in to the **Group Moderator** as inappropriate content by creating a **Content Report**.  
2.3.8. A **Group Member** can see a list of all **Post**s in the **Group**s they are in ordered by published time from the newest to the oldest on the **Group**'s **Post**s feed.

### 3. Public User

**3.1. General**  
3.1.1. A **Public User** can read **Post**s of any **Logged-in User** and in any **Group**.  
3.1.2. A **Public User** cannot write a **Post**.  
3.1.3. A **Public User** cannot join a **Group**.  
3.1.4. A **Public User** cannot write a **Comment** in any **Post**.  
3.1.5. A **Public User** cannot reply to any **Comment**.  
3.1.6. A **Public User** can search for **Post**s in all **Group**s or in specific **Group**, and can also search for **Group**s.  
3.1.7. A **Public User** cannot see a list of **Group Member**s of a **Group**.

**3.2. Account registration**  
3.2.1. A **Public User** can sign up to create an account and may later log in to get the privileges of the **Logged-in User**.  
3.2.2. A **Public User** can sign up with their social media account including Facebook, Twitter, and LINE.  
3.2.3. A **Public User** can sign up with an email/password pair.  
3.2.4. A **Public User** who sign up with an email/password pair must verify their email.  
3.2.5. If a **Public User** sign up with an email/password pair, they must receives an email providing a way to verify their email.

### 4. Post

4.1. A **Post** is digital content created by a **Logged-in User**. It consists of title and body text and may have a cover image.  
4.2. A **Post** must be created by a **Logged-in User**.  
4.3. A **Post** can be edited and deleted by its author (**User**).  
4.4. A **Post** can be read by any **Public User** and any **Logged-in User**.  
4.5. A **Post** can have **Comment**s.
4.6. A **Post** can be upvoted or downvoted by a **Logged-in User**.
4.7. A **Post** must have title and body text.  
4.8. A **Post** may have cover image.  
4.9. The body text of a **Post** may contain images.  
4.10. A **Post** can be hidden from all **Logged-in User**s and **Public User**s by a **Platform Moderator** or by a **Group Moderator** if it's a **Post** in a **Group**.  
4.11. A hidden **Post** cannot be seen from the **Logged-in User**s and **Public User**s.

### 5. Comment

5.1. A **Comment** is digital content created by a **Logged-in User** for a **Post** as a commentary or added discussion to the **Post**.  
5.2. A **Comment** must be created by a **Logged-in User**.  
5.3. A **Comment** can be edited, and deleted by its author (**User**).  
5.4. A **Comment** can be read by any **Public User** and any **Logged-in User**.  
5.5. A **Comment** can be upvoted or downvoted by a **Logged-in User**.  
5.6. A **Comment** can be replied with another **Comment** created by a **Logged-in User**.  
5.7. A **Comment** can be hidden from all **Logged-in User**s and **Public User**s by a **Platform Moderator** or by a **Group Moderator** if it's a **Comment** in a **Group**.  
5.8. A hidden **Comment** cannot be seen from the **Logged-in User**s and **Public User**s.

### 6. Platform Moderator

6.1. A **Platform Moderator** is someone who moderate the content of the platform. They are distinct from normal user like **Public User** and **Logged-in User**.
6.2. A **Platform Moderator** can see a list of **Content Report**s of a **Post**.  
6.3. A **Platform Moderator** can see a list of all **Content Report**s of all **Post**s.  
6.4. A **Platform Moderator** can hide **Post**s, **Comment**s, and **Group**s that are reported by the **Logged-in User**s as inappropriate from all **Logged-in User**s and **Public User**s.  
6.5. A **Platform Moderator** can see hidden **Post**s, **Comment**s, and **Group**s.

### 7. Content Report

7.1. A **Content Report** is digital content created by a **Logged-in User** to report a content on the platform as inappropriate.  
7.2. A **Content Report** consists of the issuer (the **Logged-in User** who created this report), the description of how it is considered to be inappropriate, and the content that is being reported i.e. **Post**, **Comment**, or **Group**.

### 8. Chat Room

**8.1. General**  
8.1.1 A **Chat Room** is a _real-time_ communication channel that allows **Logged-in User**s to communicate with each other in _private_.  
8.1.2. The content sent and received within a **Chat Room** can only be seen by the **Chat Room Member**.  
8.1.3. A **Chat Room Member** is a **Logged-in User** who have joined the **Chat Room**.  
8.1.4. A **Chat Room** can be created by a **Logged-in User** to initiate a conversation with another **Logged-in User**.  
8.1.6. There are 2 types of **Chat Room**: 1. **Personal Chat Room** and 2. **Group Chat Room**.  
8.1.7 The content sent and received within a **Chat Room** is called **Chat Room Content**.  
8.1.8. **Chat Room Content** must be one of these types:

- Text message including clickable links.
- Image file i.e. .png, .jpg/.jpeg, .gif, .webp

**8.2. Personal Chat Room**  
8.2.1. A **Personal Chat Room** is a real-time communication channel that allows 2 **Logged-in User** to communicate with each other in private.  
8.2.2. The content sent and received in a **Personal Chat Room** must not be accessible from other parties. Neither **Logged-in User** nor **Public User**.

**8.3. Group Chat Room**  
8.3.1. A **Group Chat Room** is a real-time communication channel that allows all **Group Member**s in a **Group** to communicate with each other in private.  
8.3.2. The content sent and received in a **Group Chat Room** must not be accessible from other parties outside of the **Group**.
