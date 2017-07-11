
..... Easier Steps to Install...

1. clone repo

# git clone https://github.com/pratiks/mongo_express_api

2. install packages of your project

# cd mongo_express_api
# npm install 

3. Pull down the mongodb image & start the container 

# docker pull frodenas/mongodb
# docker run -d --name mongodb -p 27017:27017 frodenas/mongodb --smallfiles

4. Check if you have a container running, you should see the container hash and status of "up",

# docker ps 

5. Start app 

# npm start

6. Navigate to localhost:8000 for app demo.



