# Build-a-Webshop-Angular-Node.js-TypeScript-Stripe

https://www.youtube.com/watch?v=Kbauf9IgsC4

https://github.com/bobangajicsm/E-Commerce-Store

https://raw.githubusercontent.com/RodrigoMvs123/Build-a-Webshop-Angular-Node.js-TypeScript-Stripe/main/README.md



Build a Webshop – Angular, Node.js, TypeScript, Stripe

https://www.youtube.com/watch?v=Kbauf9IgsC4



Bash
npm i @angular/cli014.2.1
ng new store - - routing - -skip-test - - minimal 
package.json 

Terminal 
cmd
+ git bash 
- ng serve
      - no 
Angular Live Development  Server is listening on local host: 4200, open your browser on 
http://localhost:4200/ 

https://material.angular.io/components/categories 
Terminal 
clear 
ng add @angular/material
- y
- y
- y 
clear 

https://tailwindcss.com/

           - https://tailwindcss.com/docs/guides/angular
           - npm install -D tailwindcss postcss autoprefixer
           - npx tailwindcss init

 
Add the Tailwind directives to your CSS
https://tailwindcss.com/docs/guides/angular
@tailwind base;
@tailwind components;
@tailwind utilities;

Terminal Git Bash 
cd ./src/app/components/
ng g c header 

Terminal 
Git Bash
ls
cd ..
cd pages /
ng g c home 

cd src/app/pages/home/components/
ng g c product-box

ls
cd ..
clear
ng g c cart

ls
cd ..
cd services/
clear
ng g s cart

https://fakestoreapi.com/

clear 
ng g s store

https://stripe.com/

npm i @stripe/stripe-js@1.35.0

cd server/
npm init -y 
clear
npm i cors@2.8.5 express@4.18.1 stripe@10.7.0

node server.js 
