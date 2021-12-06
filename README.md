# tw-starter

Install Tailwind CSS as a PostCSS plugin with JIT mode

This is a boilerplate for Tailwind CSS installed as a postCSS plugin and configured for two modes - Watching file changes for development and optimizing for production:

How to use
Step 1:
npm install

Step 2:
npm run build

Watches files as you make changes to your index.html within public folder

Step 3:
npm run prod

Note to Windows users:

If not working properly, change the build script to
"build": "set TAILWIND_MODE=watch&postcss tailwind.css -o ./public/styles.css -w --verbose"