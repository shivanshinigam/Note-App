# Note App

**Note App** is a simple and efficient note-taking application built with **React**. It allows users to add, edit, and delete notes while storing them locally using **localStorage** for persistent storage. The app is designed with responsiveness in mind, making it compatible across various devices like mobile, tablets, and desktops.

## Features

- **Create New Notes**: Users can add new notes with a default title and body.
- **Edit Existing Notes**: Users can edit the title and body of any note.
- **Persistent Storage**: Notes are stored in the browser's `localStorage`, which ensures that they are available even after closing the app or refreshing the page.
- **Offline Support**: Thanks to the service worker, the app is capable of caching content and functioning offline, making it accessible without an internet connection after the initial load.
- **Responsive Design**: The app is designed to work seamlessly on devices of all sizes.

## Tech Stack

- **React**: The app uses React to build a dynamic user interface.
- **CSS**: For styling the components, following a modular approach.
- **localStorage**: Ensures that notes persist across page reloads and sessions.
- **Service Worker**: To enable offline functionality and improve load times.

## Getting Started

### Prerequisites

- **Node.js**: Make sure that Node.js is installed on your machine. You can download it from [here](https://nodejs.org/).

Usage
Upon loading the app, users can add new notes, which will be saved in the browser’s localStorage.
To edit a note, simply click on it, modify the title or body, and the changes will be automatically saved.
Notes will persist across sessions, even after the browser is closed and reopened.


📷Screenshots
