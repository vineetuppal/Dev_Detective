# DevDetective

DevDetective is a sleek and user-friendly web application that allows users to search and view GitHub profiles. It features a dark mode toggle for an enhanced viewing experience and displays various statistics about a GitHub user, such as repositories, followers, following, and more.

## Features

- **Search GitHub Profiles**: Enter a GitHub username to fetch and display profile details.
- **Profile Details**:
  - Avatar
  - Name and Username
  - Join Date
  - Bio
  - Repositories, Followers, and Following
  - Location, Website, Twitter, and Company
- **Dark Mode Toggle**: Switch between light and dark themes for a personalized experience.
- **Responsive Design**: Works seamlessly on all devices.


## Tech Stack

- **HTML**: Structure of the application.
- **CSS**: Styled using modern techniques for responsiveness and aesthetics.
- **JavaScript**: Handles dynamic content, API integration, and user interactions.
- **GitHub API**: Fetches user profile data.

## Usage

1. Enter a GitHub username in the search bar.
2. Press `Enter` or click the search button to fetch the user's profile.
3. Toggle between light and dark modes using the button in the top-right corner.

## File Structure

```
DevDetective/
├── assets/
│   ├── images/
│   │   ├── demo.png
│   │   ├── moon-icon.svg
│   │   └── sun-icon.svg
│   └── styles.css
├── index.html
└── script.js
```


### Example API Endpoint:
```bash
https://api.github.com/users/{username}
```
Replace `{username}` with the desired GitHub username.

