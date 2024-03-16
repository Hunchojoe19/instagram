# Fullstack Instagram Clone Tutorial

# Instagram Application

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://your-build-link.com)

This is a simple Instagram application built using Firebase, Chakra UI, and React JS.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- User authentication using Firebase Auth.
- Real-time database with Firestore for storing user data and posts.
- Integration with Chakra UI for sleek and responsive user interface.
- React JS for building dynamic and interactive components.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Hunchojoe19/instagram.git
   ```
2. Navigate into the project directory:

cd instagram 3. Install dependencies:
npm install

## Firebase Setup

Create a Firebase project and set up Firestore and Authentication.

Create a .env file in the root directory and add your Firebase configuration:

plaintext
Copy code
VITE_FIREBASE_API_KEY=your-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your-sender-id
VITE_FIREBASE_APP_ID=your-app-id
VITE_FIREBASE_MEASUREMENT_ID=your-measurement-id

## Usage

Start the development server:
npm run dev
Open your browser and visit http://localhost:3000.

You can now sign up, log in, and start using the Instagram application.

## Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/my-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/my-feature).
Create a new Pull Request.
