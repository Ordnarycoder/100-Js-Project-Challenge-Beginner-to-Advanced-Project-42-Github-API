# GitHub User Info

## Description
The **GitHub User Info** app is a modern web application built with HTML, JavaScript, and Bootstrap. It allows users to fetch and display details of a GitHub user by simply entering their username. The app utilizes the GitHub API to retrieve information such as the user's name, bio, repositories, followers, and following count.

---

## Features
- Fetches user data directly from the GitHub API.
- Displays user profile information in a clean, modern design.
- Responsive layout with Bootstrap for mobile and desktop users.
- Error and feedback messages for invalid inputs or API issues.

---

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.).
- An active internet connection to access the GitHub API.

### Steps to Run Locally
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd github-user-info
   ```
3. Open the `github_api.html` file in your browser to run the app.

---

## How to Use
1. Open the app in your browser.
2. Enter a GitHub username in the input field.
3. Click the **Fetch User Info** button.
4. View the user's profile details, including:
   - Name and username.
   - Bio.
   - Public repositories.
   - Followers and following count.
   - Profile picture.

---

## Project Structure
```
github-user-info/
├── github_api.html       # Main HTML file
├── README.md        # Project documentation
└── LICENSE.txt      # License file
```

---

## API Reference
The app uses the GitHub API's **Users Endpoint**:
- URL: `https://api.github.com/users/{username}`

For more details, visit the [GitHub API Documentation](https://docs.github.com/en/rest/users).

---

## Customization
- **Styling**: Modify the Bootstrap classes or add custom CSS for a unique look.
- **Functionality**: Extend the app to display additional data (e.g., repositories, organizations).

---

## Future Enhancements
- Add a search history feature.
- Display a list of public repositories.
- Allow users to save favorite profiles.
- Support for authenticated API requests to increase rate limits.

---

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.

---

## Acknowledgments
- Built with the [GitHub API](https://api.github.com).
- Designed with [Bootstrap](https://getbootstrap.com).
- Inspired by the simplicity of modern web apps.

