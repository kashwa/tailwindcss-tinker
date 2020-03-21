# tailwindcss-tinker ✨
🚀 Learning tailwind-css by example, Here is a grasp of what i did:

> \> **npm install tailwindcss**

### * Add Tailwind to my CSS
 ```
 @tailwind base;

 @tailwind components;

 @tailwind utilities;
```

### * Make command to build in `package.json`
```
"scripts": {
    "build:css": "tailwind build src/style.css -o dist/style.css"
  }
  ```
  Now you cann add classes to your components and use it out of the box, BUT
  if you want to customize your Tailwind installation, you can generate a config file:
> \> **npx tailwindcss init**

This will create a `tailwind.config.js` file where you can make your predefined styles and customizations.

--------------------------------------------------------

#### Feel free to Fork the code, use it or even modify it. 🥂
