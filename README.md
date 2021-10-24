# User Authentication Using Node Js
## Set up projects
```console
git clone https://github.com/AUIArafat/user-authentication
cd user-authentication
npm install
```

You will also need to **install the free community edition of [MongoDB](https://www.mongodb.com/download-center/community)** for [Windows](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/), [Mac](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/), or [Linux](https://docs.mongodb.com/manual/administration/install-on-linux/). Follow the installation directions for your OS.

If you followed the instructions above, you should have set the path to the MongoDB bin to your environment variables. You will need to close and reopen your console before the new environment variables are registered. **Test if it is installed and configured** with this command: `mongod --version`. If you see a version printed, then start up the database server by entering: `mongod`.

We are going to be testing our API using **Postman**. You can install it for free [here](https://www.getpostman.com/downloads/)

There are some express routes already setup in the server.js file. Also, we are using the "nodemon" package in this so our server restarts automatically. Open a new console and **start the server** by running this command:`npm run start`. You should see the message from our app.listen method and some statements about nodemon watching for changes. 
