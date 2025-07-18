⚛️ React + Vite + TailwindCSS Template
A minimal boilerplate for building modern React apps using Vite, Tailwind CSS, and useful tools like Redux Toolkit, React Router, and ESLint.

🚀 Features
Vite – Lightning-fast bundler and dev server

React – Modern UI framework

Tailwind CSS – Utility-first CSS

Redux Toolkit – Simplified state management

React Router – Client-side routing

React Hot Toast – Elegant toast notifications

ESLint – Linting for clean code

⚙️ Installation
1. Create Vite App
bash
Copy
Edit
npm create vite@latest
cd your-project-name
Choose:

Framework: React

Variant: JavaScript or TypeScript

2. Install Tailwind CSS
bash
Copy
Edit
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
Update tailwind.config.js:

js
Copy
Edit
export default {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: { extend: {} },
  plugins: [],
}
Add to src/index.css:

css
Copy
Edit
@tailwind base;
@tailwind components;
@tailwind utilities;
3. Install Packages
bash
Copy
Edit
npm install
4. Run Dev Server
bash
Copy
Edit
npm run dev
📦 Main Packages
Dependencies:

react, react-dom

@reduxjs/toolkit, react-redux

react-router-dom, react-hot-toast

lucide-react

Dev Dependencies:

vite, @vitejs/plugin-react

tailwindcss, postcss, autoprefixer

eslint, eslint-plugin-react, eslint-plugin-react-hooks

📁 Project Structure
css
Copy
Edit
src/
├── assets/
├── components/
├── pages/
├── App.jsx
├── main.jsx
└── index.css
Other files:

.eslintrc.js

tailwind.config.js

vite.config.js

package.json

📌 Scripts
npm run dev – Start dev server

npm run build – Production build

npm run preview – Preview build

npm run lint – Lint your code

✅ Ready to Build#   P a s t e A p p  
 