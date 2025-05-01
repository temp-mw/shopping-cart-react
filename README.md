# shopping-cart-react

 A basic shopping cart built using Reactjs that lets you sort, filter and add products to the cart.
 
### Technologies Used :
  * React-JS
  * React Hooks
  * Netlify.com (for hosting)
  
### How to Run Locally :

1. Clone the Repository
  
     `git clone https://github.com/rajat2502/shopping-cart-react`

2. cd into Events-Console
  
      `cd shopping-cart-react`
      
3. Install all dependencies
      
      `npm install`
      
4. Start Local Server
      
      `npm start`

Local:
1. mw-app-prefix-consumer-group-issues > Add ngrok
   MW_TARGET: https://aa79-14-195-204-154.ngrok-free.app

2. Update index.html

3. Run cmds as:
```angular2html
cd ~/workspace/integrations/misc/github-integration/examples/shopping-cart-react
npm run build
NODE_TLS_REJECT_UNAUTHORIZED='0' npx @middleware.io/sourcemap-uploader upload --apiKey kwksdufvomzzbjtzvyvqvkcznnzjaelgbhyk -bu https://bwfhm.mw.lc/api/v1/rum/getSasUrl -p build --appVersion 1.0.0
serve build
```

Stage:
1. Update index.html

2. Run cmds as:
```angular2html
cd ~/workspace/integrations/misc/github-integration/examples/shopping-cart-react
npm run build
NODE_TLS_REJECT_UNAUTHORIZED='0' npx @middleware.io/sourcemap-uploader upload --apiKey <KEY> -bu <TARGET>/api/v1/rum/getSasUrl -p build --appVersion 1.0.0
serve build
```