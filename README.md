[![Build Status](https://travis-ci.org/Dianawats/fast-food-fast.svg?branch=api)](https://travis-ci.org/Dianawats/fast-food-fast)
[![Coverage Status](https://coveralls.io/repos/github/Dianawats/fast-food-fast/badge.svg?branch=api)](https://coveralls.io/github/Dianawats/fast-food-fast?branch=api)

# Fast-Food-Fast


### Project Overview
Fast-Food-Fast is a food delivery service app for a restaurant.

### Required Features
```
- Users can create an account and log in.
- A user should be able to order for food.
- The admin should be able to add,edit or delete the fast-food items.
- The admin should be able to see a list of fast-food items.
- The Admin user should be able to do the following:
          a. See a list of orders
          b. Accept and decline orders
          c. Mark orders as completed.
- A user should be able to see a history of ordered food. 
```
## Getting Started
This following information will help you setup and run the application on your local machine.

### Prerequisites

You will need the following:
- Internet
- HTML5
- GIT
- IDE
- Postman

## Project links:
**User Interface:** 
The user interface pages for this project are hosted this url: (git clone https://github.com/Dianawats/fast-food-fast.git`)
The code for the UI templates can be accessed using the URL: 
(https://github.com/Dianawats/fast-food-fast.git`)

**API endpoints:** The code for the endpoints can be found using the URL: (https://github.com/Dianawats/fast-food-fast/tree/api)


## Project functionality
**Interface**
* User(client/admin) can signup and login.
* Client can order for food.
* Admin can see a list of orders.
* Admin can accept and decline offers.
* Admin can mark orders as completed.
* Client can see a history of ordered food.

**API endpoints**
* Get a list of all orders.
* Fetch a specific order.
* Place a new order.
* Update the status of an order.

## Getting the application on the local machine.
Clone the remote repository to your local machine using the following command: `git clone https://github.com/Dianawats/fast-food-fast.git`
You can now access the project on your local machine by pointing to the local repository using `cd` and `code .` if using Visual Studio code will open the code location.
Create a virtual environment in the local repository using the following code: `python -3 -m venv env`
Activate the virtual environment: `venv/scripts/activate`

## Installing dependencies.
To install all the required extensions for project, use the following command: `pip install -r requirements.txt`

## Running tests:
**Testing the API endpoints.**
Run the `run.py` file and test the endpoints in Postman as shown below:

|     Endpoint                        | Verb          | Action                     |   Parameters     |
| ----------------------------------- |:-------------:|  ------------------------- | ----------------- |
| /api/v1/orders                      | GET           | Get all orders          | none   |
| /api/v1/orders/<int:orderId>        | GET           | Get a specific order          | order_id(URL)  |
| /api/v1/orders                   | POST          | Place a new order             | client,contact,order_item,price |
| /api/v1/orders/<int:orderId>| PUT          | Update status of an order | order_status,order_id(URL)  |
| /api/v1/orders/<int:orderId> | DELETE     | Delete a specific order | order_id(URL) |

**Running unittests for the API endpoints**
Use the `pytest tests --cov=api --cov-report term-missing` command to run the tests and get the coverage report.

## Deployment:
The app has been hosted on heroku, use the following link (https://diana-fast-food-fast.herokuapp.com/api/v1/orders)
## Contributing

dianakiznaki@gmail.com

## Authors

* **Diana Nakiwala**





