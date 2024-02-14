## Project Created with Command
npx create-react-app shopper --template redux

## Tailwind CSS
-> Free Components can be obtained by this site:
https://tailwindui.com/components/preview

## Intall Tailwing CSS
npm install tailwindcss@latest

## after installation of tailwing, use the command to initialize it
npx tailwindcss init 

## the configure file of tailwing created, now go to the site
https://tailwindcss.com/docs/guides/create-react-app

Now, paste this "./src/**/*.{js,jsx,ts,tsx}" on conent in tailwind configuration

## In index. css, paste these decorators
@tailwind base;
@tailwind components;
@tailwind utilities;

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