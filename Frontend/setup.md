## How to setup Tailwind CSS

Step 1: Installation- 
run the following command

```
npm install -D tailwindcss
npx tailwindcss init
```
Step 2: Update tailwind.conf.js file to incllude this line:
content: ["*.html"],
```
content: ["*.html"]
```
Step 3: Create srs/input.css to include
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Step 4: Include the src/output.css file to your html

Sep 5: Run the following command
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```



