# mern-mongo-basic

npm init
npm i express --save
npm i body-parser --save
npm i nodemon --save-dev
npm i mongodb --save
npm i mongoose --save

const uri = "mongodb+srv://admin:oxddFgqA0BT3w2f7@cluster0.76p3z.mongodb.net/productDB?retryWrites=true&w=majority";

"start": "nodemon app.js"

POST
http://localhost:3000/products

{
  "name": "apple",
  "price": 0.99
}

GET
http://localhost:3000/products


DeprecationWarning: current Server Discovery and Monitoring engine is deprecated, and will be removed in a future version. To use the new Server Discover and Monitoring engine, pass option { useUnifiedTopology: true } to the MongoClient constructor.
