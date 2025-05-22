# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

Here's a professional and well-structured `README.md` file for your React Bootstrap-based portfolio project:

---

```markdown

Personal Portfolio Website

This is a modern and responsive **Personal Portfolio Website** built using **React.js** and **React-Bootstrap**. It includes animated sections, tabbed project displays, contact forms, and a clean UI—perfect for showcasing your work, skills, and ways to get in touch.

---

Features

Clean & responsive design
Project showcase with tabs
Contact form with backend integration
Social media footer
Track-on-screen animations
 Reusable components

---

## 🛠️ Technologies Used

| Frontend      | Utility & Libraries        |
|---------------|----------------------------|
| React.js      | React-Bootstrap            |
| HTML5 & CSS3  | Animate.css                |
| JSX           | react-on-screen visibility |
| Bootstrap Grid System | Font/SVG Icons     |

---

## 📁 Project Structure

```

📦 src
├── assets
│   └── img                  # All images and icons
├── components
│   ├── ProjectCard.js       # Reusable project card component
│   ├── Projects.js          # Section to display projects in tabs
│   ├── Contact.js           # Contact form with validations
│   └── Footer.js            # Footer with social links
├── App.js                   # Root component
└── index.js                 # Entry point

```

---

## 📸 Screenshots

| Projects Section | Contact Form | Footer |
|------------------|--------------|--------|
| ![Projects](./assets/img/project-img1.png) | ![Contact](./assets/img/contact-img.svg) | ![Footer](./assets/img/nav-icon1.svg) |

---

## 🧩 Component Overview

### 🧱 `Projects.js`
- Displays portfolio projects in a tabbed layout
- Uses `ProjectCard` to render individual projects
- Animate-on-scroll using `react-on-screen`

### 🧱 `ProjectCard.js`
- A reusable component to show project image, title, and description

### 🧱 `Contact.js`
- Form with fields: first name, last name, email, phone, and message
- Sends data to a backend endpoint (`/contact`)
- Shows status messages

### 🧱 `Footer.js`
- Displays social media icons
- Centered layout with copyright

---


## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-portfolio.git
cd your-portfolio
````

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

---

Deployment

You can deploy this app to:

*Vercel*
*Netlify*
*GitHub Pages*
*Firebase Hosting*

Just build your app:

```bash
npm run build
```

And upload the `build` folder to your host.



