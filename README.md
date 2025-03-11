# VibeSphere
Real Time Social media website with real time counters of users like, comments and all.


* Project Overview
Name: VibeSphere

* Concept: A dynamic web application that mimics a social media platform with real-time updates (e.g., likes, posts) and syncs interactions to external platforms like X. Users can post content, interact with others, and see live changes across all connected clients and linked social media accounts.

* Objective: Build a scalable, interactive platform emphasizing real-time functionality and cross-platform integration.
Target Audience: Social media users, developers learning real-time apps, and communities seeking a custom hub.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Features:

* Core Features
1. User Profiles
- Sign-up/login via email or OAuth (Google, X).
- Profile includes username, bio, avatar, and linked social media accounts (e.g., X handle).
- 
2. Post Creation
- Text posts (280-character limit), image uploads, or URLs.
Option to auto-share to X upon posting.

3. Real-Time Interactions
- Like/comment on posts with instant updates for all users.
- Live feed showing newest posts and interactions.
- Browser notifications for likes/comments (if permitted).
  
4. Cross-Platform Sync
Likes on SyncSphere update corresponding X posts.
Pull external likes/comments into SyncSphere (future enhancement).

6. Dynamic Feed
Sorted by recency or popularity (likes).
Filter options: “All,” “Following,” “Trending.”

8. Additional Features
i) Live Activity Bar
- Real-time sidebar: “User X liked Post Y.”
- Highlights trending posts/users.
  
ii) Groups
Create/join groups with separate feeds.
Public or private access.

iii) Analytics
Post stats: likes, shares, reach.
Visual graphs (e.g., engagement over time).

iv) Custom Reactions
Emoji-based reactions beyond likes.
Sync as comments on external platforms.

v) Progressive Web App (PWA)
Offline access and mobile app-like experience.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Tech Stack
* Frontend
- React.js: Dynamic UI with component reusability.
- Redux Toolkit: State management for posts, user data.
- Socket.IO-Client: Real-time updates from server.
- Axios: HTTP requests to backend API.
- Tailwind CSS: Responsive, modern styling.

* Backend
- Node.js + Express: Server-side logic and API endpoints.
- Socket.IO: WebSocket for real-time communication.
- MongoDB: NoSQL database for users, posts, interactions.
- Redis: Cache trending data or session management.
- Twitter-API-V2: X integration for posting/liking.

* Tools & Services
- X API: Sync posts and interactions.
- Firebase Cloud Messaging: Push notifications.
- Multer: Image upload handling.
- dotenv: Environment variable management.

* Deployment
- Vercel: Frontend hosting.
- Heroku/AWS EC2: Backend with WebSocket support.
- MongoDB Atlas: Cloud database.
  
-------------------------------------------------------------------------------------------------------------------------------------------------------------------


# Development Plan
* Prerequisites
Software: Node.js (v16+), npm, MongoDB (local or Atlas), Git.
Accounts: X Developer Portal (API keys), code editor (e.g., VS Code).

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

Full Development Plan : https://www.notion.so/VibeSphere-1b3c2b52582c8079ba60d02bb65f5db1?pvs=4

