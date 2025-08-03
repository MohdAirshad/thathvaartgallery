# thathvaartgallery

# To run this, install tailwindcss  CLI
npm install tailwindcss @tailwindcss/cli

#import tailwindcss
@import "tailwindcss";

#Start tailwindcss CLI build process
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

#Start using tailwindcss with the html
