Router Project
This is a React project that uses Tailwind CSS for styling and React Router for navigation.

Table of Contents
Installation
Usage
Available Scripts
Configuration
Project Structure
Dependencies
Contributing
License

Installation
To get started with the project, clone the repository and install the dependencies:
git clone https://github.com/yourusername/router-project.git
cd router-project
npm install

Usage
To start the development server, run:
npm start

Available Scripts
In the project directory, you can run:

npm start: Starts the development server.
npm run build: Builds the app for production to the build folder.
npm test: Launches the test runner in the interactive watch mode.
npm run eject: Removes the single build dependency from your project.

Configuration
Tailwind CSS
The project uses Tailwind CSS for styling. The configuration can be found in tailwind.config.js:

module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {
      fontFamily: {
        inter: ["Inter", "sans-serif"],
      },
      colors: {
        richblack: {
          5: "#F1F2FF",
          25: "#DBDDEA",
          100: "#AFB2BF",
          200: "#999DAA",
          700: "#2C333F",
          800: "#161D29",
          900: "#000814",
        },
        blue: {
          100: "#47A5C5",
        },
        pink: {
          200: "#EF476F",
        },
        yellow: {
          50: "#FFD60A",
        },
      },
    },
  },
  plugins: [],
};

Project Structure
router-project/
├── node_modules/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   ├── index.js
│   ├── ...
├── .gitignore
├── package.json
├── package-lock.json
├── tailwind.config.js
└── README.md

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
