## :star2: About the Project
MyShop is an Ecommerce web application built with Next.js and MongoDB.

https://github.com/Kazakoff/myShop-Next-full-website-main.git


# 🏃‍♀️ Running

-   Clone repo Run `git clone https://github.com/pawanpk87/myShop-Ecommerce-website.git`
-   Run `npm i`
-   Run `npm run dev`
-   See `http://localhost:3000`



db.createUser(
  {
    user: "shop",
    pwd: "shop",  
    roles: [
       { role: "readWrite", db: "myShop-Next-full" }
    ]
  }
)
