## Step by step guide on how to run the docker project
Navigate to the frontend folder and run the following command
```javascript
docker build --tag frontend .
```
<br>

Do the same in the backend folder
```javascript
docker build --tag backend .
```
<br>

Check if the images have been created
```javascript
docker images
```
<br>

Using docker-compose
```javascript
docker-compose up
```
<br>

We specified port 5500 for our localhost, where the project will be running on
```javascript
localhost:5500
```
<br>

To stop the project
```javascript
docker-compose down
```
