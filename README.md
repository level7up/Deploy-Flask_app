

API endpoint: [https://c7bb121ab07c0b712d7dbed0c5639002.gr7.us-west-2.eks.amazonaws.com/](https://c7bb121ab07c0b712d7dbed0c5639002.gr7.us-west-2.eks.amazonaws.com/)

The Flask app that will be used for this project consists of a simple API with three endpoints:
    
- `GET '/'`: This is a simple health check, which returns the response 'Healthy'. 
- `POST '/auth'`: This takes a email and password as json arguments and returns a JWT based on a custom secret.
- `GET '/contents'`: This requires a valid JWT, and returns the un-encrpyted contents of that token. 

There is a Postman Collection in the file: udacity-eks.postman_collection.json 
