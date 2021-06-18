1. npm install tailwindcss
2. create css folder -> add tailwind.css file -> add tailwind classes
@tailwind base;
@tailwind components;
@tailwind utilities;

3. npm tailwindcss-cli build css/tailwind.css -o build/tailwind.css
4. npm i -D tailwindcss postcss autoprefixer vite
5. npx tailwindcss init -p
6. edit tailwind.config.js --

'./src/**/*.html',
'./src/**/*.js',
