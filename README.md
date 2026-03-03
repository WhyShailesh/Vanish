Vanish

A Privacy-First Ephemeral Chat Application for Android

Vanish is a real-time chat application designed with privacy as the core principle. It does not require email, phone number, or password authentication. Conversations exist only while users are connected and are never stored.

Features:
No login system (device-based anonymous identity
Permanent, unique username ownership
Username change support
Real-time one-to-one chat
Room-based group chat with admin control
OArchitecture

Frontend:

Android (Kotlin, Jetpack Compose)
MVVM Architecture
Socket.IO client

Backend:
Node.js with Socket.IO
In-memory message relay (no persistence)
Deployable on Fly.io

Database:
Firebase Firestore (stores only user metadata and presence)
Messages are transmitted via WebSockets and exist only in server memory during delivery.ffline discoverability toggle
No message storage in database
Screenshot and screen recording protection
Automatic session termination

