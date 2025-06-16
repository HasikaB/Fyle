
# GitHub User Repository Viewer

The GitHub User Repository Viewer is an HTML application designed to provide users with a simple and interactive interface for exploring GitHub user profiles and repositories. This document serves as a guide to understand the functionality of the application, its usage, and the underlying code structure.

## How to Use

1. Open the HTML file (`index.html`): Launch the application in a web browser.

2. Enter a GitHub username: Input the desired GitHub username in the provided text field.

3. Click "Search": Execute the search by clicking the "Search" button.

4. View User Information: Explore the user's profile information, including name, bio, location, and Twitter link (if available).

5. Browse Repositories: Scroll through the paginated list of the user's repositories, showcasing project titles, descriptions, and associated technologies.

6. Navigate Pages: Utilize the "Previous" and "Next" buttons for seamless navigation through repository pages.

## Code Structure

- **HTML (`index.html`):** Defines the application structure, including input fields, containers for user profile information and repositories, and embedded CSS styles.

- **CSS (Embedded):** Styles the visual appearance of the application, providing a clean and user-friendly interface.

- **JavaScript (Embedded):** Manages user interactions, fetches data from the GitHub API, and dynamically updates content based on fetched data.

## GitHub API Integration

The application integrates with the GitHub API using two main endpoints:

1. **User Information Endpoint:**
   - URL: `https://api.github.com/users/:username`
   - Retrieves details about the specified GitHub user, such as avatar, name, bio, location, and Twitter link.

2. **Repository Information Endpoint:**
   - URL: `https://api.github.com/users/:username/repos`
   - Fetches a paginated list of repositories owned by the specified GitHub user, including project title, description, language, and topics.

## Notes

- **Username Entry:** Ensure correct entry of the GitHub username to fetch the desired user's data.

- **Error Handling:** The application displays error messages in case of issues with GitHub API requests.

- **Customization:** The code and interface are customizable to suit specific project requirements and preferences.

