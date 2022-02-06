## Build

```bash
npx parcel src/index.html
```

To re-create this type of build:

https://tailwindcss.com/docs/guides/parcel

## Create your project
# Terminal
```bash
mkdir my-project
cd my-project
npm install -D parcel
mkdir src
touch src/index.html
```

## Install Tailwind CSS
# Terminal

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Configure your template paths
# tailwind.config.js
```bash
  content: [
    "./src/**/*.{html,js,ts,jsx,tsx}",
  ],
```

## Add the Tailwind directives to your CSS
# style.css
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Start your build process
# Terminal
```bash
npx parcel src/index.html
```

## Start using Tailwind in your project
# index.html
```bash
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./index.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```
