This is learning section to make web based app with React js and Tailwind CSS framework.

to start from scratch:

1. install react:
   npx create-react-app <folder_name>

2. install Tailwind CSS package & stuff:
   npm install tailwindcss postcss-cli autoprefixer

3. install Tailwind CSS js:
   npx tailwind init tailwind.js --full

4. make post CSS config file:
   touch postcss.config.js

5. make tailwind.css file

6. config package.json, then change and add some script in the scripts section:
   "start": "npm run watch:css && react-scripts start",
   "build": "npm run build:css && react-scripts build",
   "build:css": "postcss src/assets/tailwind.css -o src/assets/main.css",
   "watch:css": "postcss src/assets/tailwind.css -o src/assets/main.css"

7. Finally, start program & make some web:
   npm start

Source: https://www.youtube.com/watch?v=FiGmAI5e91M
