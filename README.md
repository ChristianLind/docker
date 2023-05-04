# Description
The developers for this project are: Kasper and Christian
<br>
The developers for the entire project, which have been used as the base, are: Victor, Nikolaj, Kasper and Christian

# Step by step guide on how to run the docker project
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
## Running the project
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
