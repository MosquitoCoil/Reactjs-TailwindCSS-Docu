# Reactjs-TailwindCSS-Docu
From the scratch
```
Download VS Code and Node Js
Open VS code and open terminal
Check the node js version: node -v
Create a package.json file: npm init
Press "Enter" until it stops
1. Install Tailwindcss: npm install -D tailwindcss
2. Check if the tailwindcss in inside the package.json under "devDependencies"
3. Create tailwind.config.js: npx tailwindcss init
4. Edit the path inside the tailwind.config.js: content: ["./src/**/*.{html,js}"], copy this and replace the content line of code.
5. Create new folder inside the workspace: dist/index.html.
6. Change the path in tailwind.config.js: src - dist
7. Create src folder inside the workspace: src
8. Inside the src folder create input.css 
9. Then paste this inside the input.css : 
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
10. And run this command: npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
11. Create html structure inside index.html to import the output.css in 
<head>
<link rel="stylesheet" href="output.css">
</head>
12. Every time you run the project you need to run this command: npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
13. But you can put it inside the package.json to less hustle under "scripts"
paste this: "dev": "tailwindcss -i ./src/input.css -o ./dist/output.css --watch"
14. Run your project by typing this command in terminal: npm run dev
```
To start up new project run this command in terminal:
```
1. npx create-react-app my-project ("my-project" is the name of your project)
	*installed packages inside to your project
2. To install Tailwindcss in your project run this command: npx tailwindcss init
3. cd my-project (use this command to open your created project)

Create project with your name choices:
1. npm create vite@latest .
