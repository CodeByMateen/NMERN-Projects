## Project Created with Command
npx create-react-app shopper --template redux

## Tailwind CSS
-> Free Components can be obtained by this site:
https://tailwindui.com/components/preview

## Intall Tailwing CSS
npm install tailwindcss@latest

## after installation of tailwing, use the command to initialize it
npx tailwindcss init 

## the configure file of tailwind created, now go to the site
https://tailwindcss.com/docs/guides/create-react-app

Now, paste this "./src/**/*.{js,jsx,ts,tsx}" on conent in tailwind configuration

## In index.css, paste these decorators at Top
@tailwind base;
@tailwind components;
@tailwind utilities;

Add, '@tailwindcss/aspect-ratio' in plugins in tailwindcss configuration file
also do, npm install @tailwindcss/aspect-ratio

also do the same with '@tailwindcss/forms'

now, install: npm i @headlessui/react @heroicons/react

Similarly, for each tailwind component, checkout the instructions given to use them which is already present in code having commented out

Now, Tailwind is Ready for Project

# clearing un-necessary code and deleting un-necessary files
-> clean App.css
-> clear App.js header section
-> delete couterSlice.spec file in features
-> also App.css file delete it
-> clear the random imports who're using decrement, odd etc. 
-> clear Counter.js and keep only div part in only only return part

install extension of tailwind css intellisense in vscode

_____________________________________________________________________

## in features, we'll have a component file, it's api file and slice file like we have counter component contain counter.js, counterAPI.js, counterSlice.js
## and so on, we create our components in features following this style.

_____________________________________________________________________

# we have made react app router in app.js file.
to enable it we have use this command: npm i react-router-dom