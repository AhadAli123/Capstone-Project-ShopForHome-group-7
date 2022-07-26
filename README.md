STEP-1
Install Dependencies (Separate terminal)
1- For Backend -> First cd backend and than run "npm install".
2- For Frontend - cd frontend "npm i".

STEP-2 (Both are in separate terminal)
1- To Run The Backend Server Run Command.

$ cd backend $ npm install $ npm start

2- To Run The Frontend Run Command.

open new terminal
$ cd frontend $ npm install $ npm start

Env Variables
Make Sure to Create a config.env file in backend/config directory and add appropriate variables in order to use the app.

---------- We are providing our env variables on which we are running our project so if you want to use ours than just update "MONGO_URI" according to your system and remaining variables keep as it is. and if you want to use your own env variables than create config.env file in config folder (backend) and than run the project ----------

Essential Variables
➢ FRONTEND_URl=http://localhost:3000

➢ JWT_SECRET=somethingsecret

➢ MONGODB_URI=mongodb+srv://shopforhome:shopforhome@cluster0.txfxn.mongodb.net/?retryWrites=true&w=majority

➢ PAYPAL_CLIENT_ID=ASd6g52UBigl4x7hfKOla_hwLjGoOarzLwh4Z-T4lSNqpBf7Bbx1upNOXYC7LaFPMvP5Vg3fdBwEE0N5

➢ CLOUDINARY_CLOUD_NAME=shopforhome

➢ CLOUDINARY_API_KEY=259242298889797

➢ CLOUDINARY_URL=cloudinary://259242298889797:2hPaes_xI7O8cWTLT3KNxxZLBp8@shopforhome

➢ CLOUDINARY_API_SECRET=2hPaes_xI7O8cWTLT3KNxxZLBp8

➢ MAILGUN_API_KEY= write your api key

➢ MAILGUN_DOMIAN= write your mailgun domain

➢ NODE_ENV=DEVELOPEMENT

For Payement we have used the Paypal sandbox Account which is only for development and testing purpose...
    LOGIN ID is : ahadwipro@gmail.com
     PASSWORD is : Ahad@123                  
****************************************************** User can perform the following actions. *************************************************

After successfully running the project in browser.-:
➢ Sign up: User can signup in order to buy and review products.

➢ Login: After the user has sign up, the user becomes a customer,and he or she can log in with their personal information.

➢ View: The customer can see all the products in the catalog and be able to look at the products and some features on the homepage.

➢ Update Cart: customer can also add or remove products from a shopping cart.

➢ Update Cart: Customer can also give review and comments on each products.

➢ Sort : Customer can also sort product on the basis of cost,review,price,high to low, low to high price and on the basis of arrivals.

➢Review : Customer can give review and comments on each product.

================================================================================================================================================

                 Admin email = ahadwipro@gmail.com
                 Admin password = Ahad@123
------After Sigin admin can also make any user as admin. To do this CLICK on Admin then in dropdown Click on Users you will reach on User-Detail page . Then click on Edit action you will reach onEdit-User page from there u make any user as a Admin.-------------
************** Now Admin have CRUD operation on the user ,products include uploading images , stock and as well as sales. *******************

To create ,delete or update any product follow below steps-:
1]. To edit and update Go to Admin and click it than click on the products.Then you will be directed to Edit Product screen. ------- Here admin can edit and update the following things.--------

Name
Price
Discount Coupan
Upload Image
Upload Aditional Image
Category
Brand
Stock
Description
2]. To update the status of any orders follow below steps-:

Go to Admin and click on the Orders.Then you will be directed to Orders-Details Screen. click on Details box to update the status from processing to shipped or delivered as you want.

3]. To delete or update any users follow below steps-:

Go to Admin and click on the Orders.Then you will be directed to Orders-Details Screen click on Delete box to delete any user.

--------------- This is for to get all the users here you can edit and delete the users.--------
