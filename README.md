# Blog Application with React and Redux Toolkit

![localhost_3000_ (2)](https://github.com/HAWKZ4/Redux-Blog/assets/108879264/2e5b002f-430e-42ac-bb8d-d735592420e9)

Welcome to **Blog Application**!

This project is built using React and Redux Toolkit, designed to advance global state management.
<br/>
It allows users to create posts and interact with other posts through various interaction buttons.

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## ✨ Features

- **Create Posts**: Users can create new blog posts.

- **Interact with Posts**: Users can interact with posts using buttons (like, love, coffee, wow, rocket).

- **Responsive Design**: The application is responsive and works well on different devices.

- **Mock Backend**: Utilizes `json-server` as a mock backend with a local `db.json` file to store dummy data for posts and users.

## 🛠️ Installation

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/)

### Clone the repository

```bash
git clone https://github.com/HAWKZ4/Redux-Blog
cd Redux-Blog
```

### Install dependencies

```bash
npm install
```

### Start the JSON Server

In one terminal, run the following command to start the mock backend server:

```bash
json-server --watch data/db.json --port 3500
```

### Start the React app

In another terminal, run the following command to start the React application:

```bash
npm start
```

The app should now be running at `http://localhost:3000`.

## 🚀 Usage

Once the application is running, you can:

1. **Create a Post**: Click on the "Create Post" button and fill in the required fields.

2. **Interact with a Post**: Click on any of the interaction buttons (like, love, coffee, wow, rocket) to increase the count for that specific post.
