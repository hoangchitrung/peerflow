## 1. Introduction
### Name: PeerFlow
### Main goal: 
- Building real-time chat application allows users to messages and send files, messages and files are secured, optimize fee by store temporary files.
### Stakeholders: 
- Personal user that needs a lightweight communication tool, fast and private.

## 2. Functional Requirements
### 2.1 User Management
- **Sign in/up**: Username, Email, Password.
- **Profile**: Avatar, Bio, Name, Email, Phone.
### 2.2 Real-time Messaging & Voice Chat:
- **Send Text:** Users send and receive message immediately.
- **Message status:** Seen/Sent
- **Voice Chat**: Video Calling using WebRTC. 
### 2.3 Send Files:
- **Cleanup Logic:** Send files and store temporary on the server for 24 hours
- **Security & Constraints**:
	- **File Size Limit:** 20MB.
	- **Format:** .jpg, .png, .docx, .zip (no exe and sh or any execute files).

## 3. Non-functional Requirements
- **Privacy:** Just only users involved to the conversation could see the messages
- **Performance:** Could deploy smoothly on mobile device and web (Vercel/Netlify).
- **Everything Free:** Use all the free things that I could use for maintain this system for 24/7.
### 4. Tech stack
- **Front-end:** Flutter.
- **Back-end:** Firebase (Firestore, Auth, Cloud Functions).
- **Deployment:** Vercel (web version).