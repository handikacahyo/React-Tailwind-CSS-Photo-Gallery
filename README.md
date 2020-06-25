This is learning section to make web based app with React js and Tailwind CSS framework.

to start from scratch:

1. Install react :
   <br/> npx create-react-app <folder_name>

2. Install Tailwind CSS package & stuff :
   <br/> npm install tailwindcss postcss-cli autoprefixer

3. Install Tailwind CSS js :
   <br/> npx tailwind init tailwind.js --full

4. Make post CSS config file :
   <br/> touch postcss.config.js

5. Make tailwind.css file

6. Config package.json, then change and add some script in the scripts section :
   <br/> "start": "npm run watch:css && react-scripts start",
   <br/> "build": "npm run build:css && react-scripts build",
   <br/> "build:css": "postcss src/assets/tailwind.css -o src/assets/main.css",
   <br/> "watch:css": "postcss src/assets/tailwind.css -o src/assets/main.css"

7. Finally, start program & make some web :
   <br/> 7.1. npm start

Source: https://www.youtube.com/watch?v=FiGmAI5e91M
