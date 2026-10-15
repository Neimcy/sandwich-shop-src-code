# sandwich-shop-src-code

---Neimcy Fall 2026 Web Project---

The src folder to a web Project dedicated to making a full stack sandwich shop website. Allows for logins, orders, and messages.

Overview:
There are two parts of this web project, a Vue front-end, and a Node.js Server, the Database will automatically connect to the database.


Instructions on getting it set up:


For Node.js. express, sequelize, and CORS need to be installed, I'm not familiar where NPM installs those packages to, but I have used packages from both in the code.

For Vue.js, you need axios and bootstrap (latest versions) installed, I have a feeling those packages would sit in the node_modules (which isn't included with this zip)


To Run it.

1. You need to be connected to a reliable web server via Cisco anyconnect, and set to the robust vpn.

2. open a CMD and run the Node.js with 
$> node server.js

It's supposed to run on localhost:8000

3. For Vue, it's a matter of opening a CMD and then 
$> npm run dev



AN EXTRA FEATURE:
In the website, login with these credentials:

Username: DaveTheAdmin
Password: !Password12345

This is the administrator account. 

There should be a new button in the menu called "Add Sandwiches"


The website should also have form Validation for addAccount.vue, Login.Vue, Purchase.vue, and finally AddSandwich.vue
