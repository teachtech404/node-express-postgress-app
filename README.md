# Instructions
1. Download or clone the project
2. cd to folder
3. Type npm install in cmd prompt or terminal to install the node modules
4. Type npm start in cmd prompt or terminal to start the app
5. The app will be running at localhost:3000

CURL Methods
1. POST Method
curl --data "text=test&complete=false" http://127.0.0.1:3000/api/v1/sampledb

2. PUT Method
curl -X PUT --data "text=test&complete=true" http://127.0.0.1:3000/api/v1/sampledb/1

3. DELETE Method
curl -X DELETE http://127.0.0.1:3000/api/v1/sampledb/1

4. GET
Go to your browser and input http://127.0.0.1:3000/api/v1/sampledb
