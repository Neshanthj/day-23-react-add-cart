Languages used
HTML,CSS and JavaScript(React.js)
how to open react project file
- command 
- npm create vite@latest file-name -- --template react
- after created file - npm install
About Website
Shopping cart website created using "React + Vite"
App.jsx File includes 5 main components
- CardSection
- contains
 - Component that displays product details. It includes a button to add/remove items from a cart. The component takes in product details and a function to manage cart item counts. The button toggles between "Add to Cart" and "Remove from Cart," updating the cart count accordingly. The card displays product information like name, image, sale badge, price, and rating if available.
- MainSection
- contains
 - code creates a main section displaying product details from a JSON array. It iterates through the array and utilizes the CardSection component to display each product's information. The MainSection component manages the layout of these product cards and passes down a function to manage cart counts.
- NavigationBar
- contains
 - It's a navigational element that includes links for Home, About, and a Shop dropdown menu. The cart count is also displayed here, indicated by a badge next to the Cart icon. This count is received as a prop and shown in the UI.
- Header
- contains 
  -Shop in style
  -With the shop homepage template
- Footer
 - contains Copyright information

To Run Application
-npm run dev
after the above command 
the file runs in this url -http://localhost:5173/

Then i have pushed my code on github and 
deployed my task 

deployed link
-



