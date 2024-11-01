---
title: Assignment 6 - User Testing & Analysis
layout: doc
---

| Task Title                        | Instruction                                                                                               | Rationale                                                                                                                                                                                                                                                             |
|-----------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. Register and Set Up Profile     | "Create a profile with your name, expertise, interests, and experience."                                | This task introduces users to the registration and profile setup process, essential for using the app. Observing this process will show if users can easily navigate initial setup, a critical entry step for successful engagement.                                  |
| 2. Explore and Follow a Profile    | "Explore user posts and follow a user whose profile aligns with your interests."                         | This task evaluates how users navigate the app to find and connect with other users. Seeing how effectively users discover relevant profiles will highlight the app's ease of use in supporting meaningful connections, a central value of the platform for fostering collaboration and networking. |
| 3. Create and React to a Post      | "Create a post to share a startup idea and react to an existing post in the feed."                       | Testing post creation and reactions helps assess the platform's functionality for sharing ideas and feedback. This task will show how accessible and intuitive the posting and interaction options are, ensuring they effectively support users in exchanging ideas and fostering a collaborative atmosphere. |
| 4. Register for an Event and Talk to other participants | "Register for an event in the app, then start a chat with other attendees."                            | This task ensures users can seamlessly transition from registering for events to engaging with other attendees. Observing users here will reveal if the app’s design effectively promotes interactions around events, a key feature for enabling community building and idea exchange in an organized setting. |
| 5. Propose a Meeting Location in Private Chat | "Using a private chat, browse nearby meeting locations and propose one to another user."                | This task assesses how well users can arrange in-person meetings through the app, supporting the platform’s goal of facilitating real-world collaborations. Observing this interaction will indicate if the location browsing and meeting proposal features are intuitive and align with user expectations. |


## User1:
**Response to instructions:**
1. No issues with logging in and registering as a user. Clicked on the profile and asked what "NA" meant, then clicked edit.
2. After looking for a moment, they realized these were posts made by other users and noticed the usernames were just “user1,” “user2,” etc. Clicked on one of the users to view their profile and successfully followed them.
3. Clicked on "create new post" in the top-right corner and created a stuffed toy company. Wanted to see what post types were available and wasn’t interested in finding people, so they clicked on "general discussion." Their initial reaction when seeing the post was to click on the name or anything clickable. The interface made it look like the names were clickable, but the post itself wasn’t. Tried to click on the post to see if there was more detail but found it couldn’t be opened. Wanted to see if there were comments or likes, noticed there was only a "like" option, so they clicked like.
4. Clicked "event" in the top-right corner, chose "networking event," and clicked "register," successfully registering for the event. Then clicked on "Jane Smith" to view her profile, clicked "Chat" to start a conversation, and said "Hi."
5. Clicked "Chat" to enter the Private Chat section, then clicked on the chat with Alice, clicked the plus icon in the lower left, saw a list of places, clicked "Central Park," and successfully sent it. 

**Discussion:**
- Didn’t initially notice there was an option for chatting and didn’t expect it to be a private chat interface.
- Without instructions, it might be hard to know what functions are available on the site or that chatting is possible. 
- Thought that the private chat section might have other functions, like sending pictures, in addition to sending locations. 
- Found the design quite simple and bright, making information easy to find, and described the style as simple.
- Would like a search function for posts to look up certain keywords.

**Reflection:**

**Positive Experiences:** User1 easily navigated through the login and registration process, finding these entry points intuitive and straightforward. The user proceeded smoothly to the profile page, which prompted a brief question about what "NA" represented, indicating that minor clarifications in labeling could enhance user comprehension. Upon exploring the interface, User1 quickly grasped the posting feature and demonstrated curiosity about post types, opting to start a company-themed post in the "General Discussion" section. This behavior underscores the design's success in inviting exploration and encouraging users to engage with different types of content creation.
The interface's event management function worked effectively for User1. They registered for a networking event effortlessly, showing the event registration design was clear and motivating. Furthermore, User1 could navigate the networking process by following other profiles and initiating private chats, which suggests that essential social interactions were generally accessible and easy to understand. The user described the layout as "simple, bright," making information easy to locate—an affirmation of the app’s aesthetic success.

**Challenges and Suggestions:** There were, however, some confusing moments that presented key improvement opportunities. For example, User1 expected clickable elements when viewing posts but found the interface misleading, as names appeared clickable while posts did not expand to reveal further details. This mismatch between visual cues and functionality led to a breakdown in user expectations, showing a possible "gulf of evaluation" where the interface didn’t provide feedback aligning with the user’s mental model.
In the chat feature, User1 initially struggled to recognize private chat options or the function to initiate direct messaging. This caused a delay as they attempted to locate a chat option, pointing to a potential need for an onboarding prompt to clarify core functionalities. Moreover, while exploring the chat, they expected the capability to send images, not just location markers, suggesting that additional communication features could enhance user experience and align with user expectations for richer interactions.
User1 also noted the absence of a post search function, expressing a desire to search posts by keywords. Integrating a search feature could improve navigation, allowing users to find relevant discussions more efficiently.

---

## User2:
**Response to instructions**
1. Had no issues logging in and registering as a user. Clicked on the profile, clicked edit, entered profile information, and saved it.
2. Clicked on User3, but couldn’t find a "follow" option due to a backend issue.
3. Clicked "create new post," entered "build a startup," selected "looking for people" as the post type, and clicked post. Tried clicking on User1's post but found it wasn’t clickable. Instead, switched to liking posts but noticed that the like function didn’t update the status, so they ended up clicking "like" multiple times.
4. Clicked "events," selected the first networking event, clicked "register," and successfully registered. Then clicked on John Doe, opened the chat, typed "hello," and sent it.
5. Entered the chat section, clicked on the chat with Alice, clicked the plus icon, found a list of addresses, but was unable to search for an address. Chose "Museum of Art" from the list and sent it.

**Discussion:**
- Suggested that several options should be made more flexible. Address selection should be searchable, and post purposes should be customizable by typing them out. Adding tags to posts and supporting content categorization in the "post explore" section would improve user experience. 
- Highlighted that the backend should be properly integrated to ensure better stability and functionality, including updating the "like" status in real-time. 
- Felt the homepage layout was somewhat illogical; posts were presented in a paginated format, but the homepage should combine highlights from posts, events, and various types of content. 
- Suggested the profile page should allow linking to social media profiles, including LinkedIn.

---

### Flaws Identified
**Clickable Elements Misleading or Unclear**
- **Issue:** Both users expected to click on posts to access more details but found posts to be static. This expectation was reinforced by visual cues (e.g., usernames or other elements appearing clickable).
- **Cause:** The design possibly mimics interactive elements without being fully functional, leading users to assume interactivity that doesn’t exist.
- **Solution:** Ensure that only functional elements appear clickable or, better yet, allow posts to expand with more detail when clicked. Adding visual consistency in clickable and non-clickable elements could reduce this confusion.
- **Classification:** Conceptual (misalignment between user expectations and functionality), **Severity:** Moderate (causes confusion but does not block progress).

**Inconsistent Chat Features and Limited Flexibility**
- **Issue:** Users expected more functionality in chat, like searchable addresses or the ability to send images. User1 noted that they only discovered chat options through exploration, suggesting chat functionality isn’t immediately obvious.
- **Cause:** The chat design may lack indicators or an onboarding guide, leaving users to infer functionality through trial and error.
- **Solution:** Enhance chat flexibility by enabling address search and image-sharing options. Additionally, provide an initial walkthrough of chat features to introduce users to the interface capabilities.
- **Classification:** Conceptual (interface expectations versus reality), **Severity:** Major (users struggle to fully utilize features).

**Limited Profile Customization and Social Integration**
- **Issue:** User2 noted that profile pages don’t allow for linking social media profiles, which could improve networking capabilities, particularly on a professional platform.
- **Cause:** Current design might prioritize simplicity over functionality, omitting deeper integration with external platforms.
- **Solution:** Include fields for social media links, especially LinkedIn, to help users build a more professional and connected profile.
- **Classification:** Linguistic (limitations in customization options), **Severity:** Minor (does not impede functionality but limits user satisfaction and engagement).

**Homepage Lacks an Engaging, Mixed-Content Feed**
- **Issue:** The homepage only displays paginated posts, missing a more dynamic combination of posts, events, and highlights that could enhance engagement and help users understand the platform’s capabilities.
- **Cause:** The homepage layout may currently be too focused on separating content by type rather than creating a seamless, holistic overview.
- **Solution:** Redesign the homepage to include an engaging mix of posts, events, and popular topics in a unified feed. Consider using a modular layout that lets users explore more varied content at a glance.
- **Classification:** Conceptual (structure and organization of content), **Severity:** Major (reduces the homepage’s potential as a starting point for exploration and engagement).
