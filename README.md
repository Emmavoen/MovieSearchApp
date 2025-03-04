# A movie search application built using React.js
# Setup Instructions
## Prerequisites
Node.js (version 14 or higher)
npm (version 6 or higher)
## Steps
1. Clone the repository:
git clone <repository-url>
cd <repository-directory>
2. Install dependencies:
npm install
3. Create a .env file:
Create a .env file in the root directory and add your API key:
VITE_API_KEY=your_api_key_here
4. Run the development server:
npm run dev
--This will start the development server and you can view the application at http://localhost:3000.
## Project Structure
src: Contains the source code of the application.

App.jsx: Main application component.
main.jsx: Entry point of the application.
index.css: Global styles.
Profile.jsx: Profile component (currently empty).
public/: Contains static assets like images and fonts.

index.html: Main HTML file.

vite.config.js: Vite configuration file.

tailwind.config.js: Tailwind CSS configuration file.

postcss.config.js: PostCSS configuration file.

.env: Environment variables file.

## Dependencies
react: React library.
react-dom: React DOM library.
axios: HTTP client for making API requests.
react-icons: Library for using icons in React.
