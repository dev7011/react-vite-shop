♦️ create project mit vite 
    npm create vite@latest mein-react-projekt -- --template react
    npm i

♦️ start
    npm run dev
    Local:   http://localhost:5173/

https://v3.tailwindcss.com/docs/customizing-colors
https://tailwindcss.com/docs/columns

♦️tailwind implementieren
  npm install tailwindcss @tailwindcss/vite   
  
  👉 nano vite.js

      plugins: [
        react(),
        tailwindcss(),
      ],

  👉 nano index.css
     @import "tailwindcss"; 