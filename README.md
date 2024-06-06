GitHub Portfolio Web App
This web application fetches your GitHub repositories using the GitHub API and displays them in a portfolio format.

Features
Fetches repositories from your GitHub account using the GitHub API.
Displays a list of repositories with pagination enabled.
Allows searching and filtering of repositories.
Shows detailed information for each repository when clicked.
Implements Error Boundary for error handling.
Provides a 404 page for handling invalid routes.
Technologies Used
React.js
Chakra UI for styling
React Router for routing
Axios for HTTP requests
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/github-portfolio.git
Navigate to the project directory:

bash
Copy code
cd github-portfolio
Install dependencies:

bash
Copy code
npm install
Create a .env file in the root directory and add your GitHub username:

plaintext
Copy code
REACT_APP_GITHUB_USERNAME=your-github-username
Start the development server:

bash
Copy code
npm start
Open your browser and go to http://localhost:3000 to view the app.

Usage
On the home page, you'll see a list of your GitHub repositories.
Use the search bar to filter repositories by name.
Click on a repository to view its detailed information.
Error Handling
If an error occurs while fetching data, an error boundary will catch and display the error.
If you navigate to a route that doesn't exist, you'll be redirected to a 404 page.
Credits
This project was created as part of Task for 3MTT Frontend Engineering – Intermediate Module Assessment.

License
This project is licensed under the MIT License.
