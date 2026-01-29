**This repository contains a Dart-based mobile application designed for CSC315.**
Its primary aim is to showcase efficient data handling and the implementation of a Repository Design Pattern to manage external web services.

##Screenshots

![App Screenshot](screenshot.png)

## Features of the app:
1. Data Retrieval: Executes HTTP GET requests to pull live content from the JSONPlaceholder ecosystem.
2. Submission Logic: Integrated methods for pushing new entries to a remote server using POST protocols.
3. State Management: Leverages the FutureBuilder widget to transition smoothly between loading indicators and populated data views.
4. Decoupled Design: Adheres to architectural best practices by isolating network calls from the presentation layer.

## Dependencies
http: ^1.x.x
flutter/material.dart
