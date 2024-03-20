# Container Challenge Exercise

Container Challenge for Cloud

## Simple Flask App

### Overview

This is a simple Flask app with a GET route that returns a success message and a POST route that echoes back posted data.

## Running the App

- Start the app: `python app.py`

## Using the App with cURL
**Test the GET route:**

curl http://localhost:5000/success

*Expected Response:* `{"message": "success"}`

**Test the POST route:**

curl -X POST -H "Content-Type: application/json" -d '{"sample":"data"}' http://localhost:5000/echo

*Expected Response:* Echoes back the JSON data sent in the request.


## Author
- Stephanie B.
<<<<<<< HEAD
=======

>>>>>>> 253d9bc8a596792b36a954ea525a35d0a0684c83
