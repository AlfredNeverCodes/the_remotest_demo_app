This repository contains a Dart-based mobile application designed for CSC315. 
Its primary aim is to showcase efficient data handling and the implementation of a Repository Design Pattern to manage external web services.

Screenshots
![App Screenshot](screenshot.png)

CSC315 Remote Demo App 🚀
A Flutter application built for CSC315 that demonstrates consuming a REST API using the Repository Pattern. The app fetches data from JSONPlaceholder and displays it in a clean, scrollable list.

Features of the app:
Data Retrieval: Executes HTTP GET requests to pull live content from the JSONPlaceholder ecosystem.

Submission Logic: Integrated methods for pushing new entries to a remote server using POST protocols.

State Management: Leverages the FutureBuilder widget to transition smoothly between loading indicators and populated data views.

Decoupled Design: Adheres to architectural best practices by isolating network calls from the presentation layer.

Dependencies
http: ^1.x.x
flutter/material.dart
