# WebApp Cloud – React + Vite + AWS Amplify

This is a modern front-end web app built using **React and Vite**, with cloud support via **AWS Amplify**. The application includes basic user profile functionality and serves as a foundation for scalable, cloud-based web apps.

---

## Features

- React 18 + Vite for blazing-fast front-end performance
- AWS Amplify authentication & config
- User Profile Component with props
- Clean folder structure with component-based architecture
- ESLint + Babel for code quality and compatibility

---

## Tech Stack

- React 18
- Vite
- AWS Amplify (Auth, Hosting)
- JavaScript (JSX)
- Babel, ESLint

---

## 🧱 Project Structure
```
webapp-cloud/
├── amplify/ # AWS Amplify backend config
│ └── (CLI-generated files)
├── public/ # Static files and Vite icon
│ └── vite.svg
├── src/ # App source files
│ ├── assets/ # Images or icons (optional)
│ ├── components/ # Reusable components
│ │ └── UserProfile.jsx # Displays user name/email
│ ├── App.jsx # Main app structure
│ └── main.jsx # React DOM mount point
├── .gitignore
├── index.html # Entry HTML file
├── vite.config.js # Vite config
├── eslint.config.js # Linting rules
├── package.json # Project dependencies
├── package-lock.json
└── README.md # Project documentation
```

---

## Installation & Running Locally

```bash
# 1. Clone the repository
git clone https://github.com/JJonnass/webapp-cloud.git
cd webapp-cloud

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
