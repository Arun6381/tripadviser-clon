Tailwind CSS
Tailwind CSS is a utility-first CSS framework that provides classes like flex, pt-4, and text-center to build custom designs directly in your markup.

Key Features
Utility-First: Build custom designs without writing CSS.
Responsive Design: Includes responsive utilities.
Customization: Configurable via tailwind.config.js.
Performance: Removes unused CSS with PurgeCSS.
Installation
Using npm
npm install tailwindcss
npx tailwindcss init

For Mac
yarn add tailwindcss
yarn run tailwindcss init

Using a CDN 
<link href="https://unpkg.com/tailwindcss@latest/dist/tailwind.min.css" rel="stylesheet">
Configuration
Edit tailwind.config.js:

js
Copy code
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {
      colors: {
        'custom-blue': '#1fb6ff',
        'custom-pink': '#ff49db',
      },
    },
  },
  plugins: [],
}
