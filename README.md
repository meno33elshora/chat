Chat Firebase App
Overview
This application is a simple chat app built with Flutter and Firebase, allowing users to register, search for friends, and send messages. It provides basic real-time messaging functionality where friends are displayed based on the last message sent, and users can search and add new friends.

Features:
User Registration & Authentication:

Users can register via email and password or log in if they already have an account.
Friends List:

Displays a list of friends, sorted by the most recent message sent or received.
Shows real-time updates for new messages, keeping conversations up-to-date.
Search Friends:

Allows users to search for friends.
Prevents duplicate friend entries; if a friend is already in your list, you cannot add them again.
Real-Time Chat:

Send and receive messages in real-time with Firebase Firestore.
Messages are timestamped and stored in the cloud.
Technology Stack:
Flutter: Used for building the cross-platform mobile UI (Android/iOS).
Firebase Authentication: Handles user registration and authentication.
Firebase Firestore: Stores user data, friend lists, and chat messages.
Firebase Storage: Optionally used for uploading image
In addition to following the status of the active user or not, and also when writing too
Screens:
Registration & Login: Users can create an account or log in with an existing one.
Friends List: Shows all friends, sorted by the latest message sent or received.
Chat Page: Send and receive messages in real-time.
Search Page: Search for friends and add them to your list (no duplicates allowed).
