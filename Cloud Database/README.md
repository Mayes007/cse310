As a computer science student, I am working to strengthen my skills in cloud integration and database management by developing a Music Playlist Manager application. This project focuses on connecting a Python application to a cloud-based Firestore database to store and manage user-created music playlists. Users can add, edit, view, and delete playlists and songs from their collection.

The program allows users to sign in, create playlists, add songs with details such as title, artist, album, and duration, and retrieve their playlists from the cloud. The system demonstrates full CRUD (Create, Read, Update, Delete) operations integrated with a cloud database.

The purpose of writing this software is to deepen my understanding of cloud technologies, real-world data organization, and application development principles, helping me grow as a computer science professional.

Software Demo Video

Cloud Database
For this project, I used Google Firestore, part of the Firebase platform, as the cloud database.

The database structure is organized as follows:

A users collection stores individual user accounts.

Each user document contains a playlists subcollection.

Each playlist document contains a songs subcollection, with each song storing details like title, artist, album, and duration.

This layered structure ensures that each user’s data is organized, separated, and easily manageable.

Development Environment
Tools: Visual Studio Code, Firebase Console

Programming Language: Python

Libraries Used:

firebase-admin for interacting with Firestore

datetime for handling timestamps and dates

Useful Websites
Firebase Admin Python SDK Documentation

Firestore Database Structure Guide

Python Firestore Tutorials