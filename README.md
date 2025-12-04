# GitHub User Profile Lookup

![GitHub User Lookup Screenshot](https://raw.githubusercontent.com/Shubham30000/github-user-lookup-test/main/screenshot.png)
_A screenshot of the application in action._

## 🚀 Live Demo

Experience the application live now:

### [🔗 Try it live here!](https://Shubham30000.github.io/github-user-lookup-test/)

## 📋 Overview

This straightforward web application provides a quick and easy way to fetch and display the GitHub account creation date for any specified username. Leveraging the GitHub API and styled with Bootstrap, it offers a responsive and intuitive interface for instant lookups.

## ✨ Features

*   **GitHub Username Lookup**: Easily search for any public GitHub user's profile.
*   **Account Creation Date Display**: Shows the exact account creation date in YYYY-MM-DD UTC format.
*   **Responsive Design**: Built with Bootstrap for a clean, modern, and mobile-friendly user interface.
*   **GitHub API Integration**: Directly interacts with the official GitHub API for reliable data retrieval.
*   **Optional Authenticated Requests**: Supports an optional `?token=` query parameter for making authenticated API requests, which can help with rate limits during development or testing.

## 🛠️ Technologies Used

*   **HTML5**: For structuring the web content.
*   **Bootstrap**: A powerful, open-source frontend toolkit for designing responsive and mobile-first websites.
*   **JavaScript (ES6+)**: For fetching data from the GitHub API, processing responses, and dynamically updating the DOM.
*   **GitHub API**: The primary data source for user profile information.

## 📦 Setup

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   A modern web browser.
*   Git installed on your machine.

### Installation

1.  **Clone the repository**:
    ```bash
git clone https://github.com/Shubham30000/github-user-lookup-test.git
    ```
2.  **Navigate into the project directory**:
    ```bash
cd github-user-lookup-test
    ```
3.  **Open `index.html`** in your preferred web browser. You can usually do this by double-clicking the file or by running `open index.html` (on macOS/Linux) or `start index.html` (on Windows) from your terminal within the project directory.

## 💡 Usage

Using the GitHub User Profile Lookup is simple and intuitive:

1.  **Access the Application**: Open `index.html` in your browser (or visit the [Live Demo](https://Shubham30000.github.io/github-user-lookup-test/)).
2.  **Enter GitHub Username**: Locate the input field with `form id='github-user-form'` and type in the GitHub username you wish to look up.
3.  **Submit**: Click the 