---
title: Assignment 4 - Backend Design & Implementation
layout: doc
---

# Github Repo

You can view the github repo on [GitHub](https://github.com/quao627/backend-starter-quao).

# Vercel Test App

You can view the test app on [Vercel](https://backend-starter-quao.vercel.app/).

# Design Reflection

Reflecting on the backend service implementation revealed several flaws in my initial design. 

1. **Profile Creation and Registration**: I initially conflated user registration with profile creation. I realized that profile details should not require a user ID, as this is established during signup. To resolve this, I separated profile creation logic from user registration, allowing users to focus solely on personal details once registered.

2. **Tags Feature Complexity**: I underestimated the complexity involved in implementing a tagging feature for posts. This necessitates an independent design approach to effectively manage tag creation and categorization. Consequently, I decided to suspend this feature until a clearer structure can be developed.

3. **Group Chat vs. Private Chat**: I reconsidered the value of the group chat feature. The app's primary goal is to foster connections among entrepreneurs, and encouraging users to initiate private chats based on shared event registrations is more aligned with this objective. Group chats may distract from meaningful interactions.

4. **Following and Follower System**: The existence of a friending system rendered the following/follower concept somewhat redundant. Instead, I opted to enhance the friending functionality, allowing users to send requests that recipients can accept or decline.

Throughout this process, I engaged in systematic self-checking by evaluating how each feature aligns with the app's core purpose. This iterative design logic not only clarified ambiguities but also led to more coherent decisions that better serve user needs. If I could revisit my initial design, I would emphasize this self-checking approach earlier, ensuring that each feature remains aligned with the overarching goals of the application.
