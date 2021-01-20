# HealthSqyre Back End Coding Challenge
This repo exists to hold the coding challenge requirements for potential candidates.
We are not concerned with completeness but rather code quality and thoughtfulness in the code. Please reach out with any clarifying questions.

## Getting Started
You can find the initial test data file in this repository.  This file includes a list of products and product attributes.

## The Challenge
You will build a simple API in python that includes a small set of common e-commerce endpoints related to a shopping cart. 

## Requirements
Create 4 endpoints that will update a shopping cart:

- [ ] **REQUIREMENT 1:** Build an endpoint that will add items into a cart object. 
- [ ] **REQUIREMENT 2:** Build an endpoint that will change the quantity of item(s) in the cart.
- [ ] **REQUIREMENT 3:** Build an endpoint that will remove item(s) from the cart. (Note: As changes are made to the cart, totals should be updated.)
- [ ] **REQUIREMENT 3:** Build a view cart endpoint that renders a json object and displays the following:
    - All cart line items, including price and quantity for each 
    - The grand total for all line items
    
#### Example Cart Response
```
{
   "cart": {
       "line_items": [
           {
               "id": 1111,
               "name": "AAA",
               "price": 100.00,
               "quantity": 1
           }
       ],
       "cart_total": 100.00
   }
}

```
NOTE: Your response could look something like this but it can differ. We would suggest you resolve against: 

- Invalid data types
- Bad requests
- Etc. 

Please provide us with documentation and an easy way to start this application.

    
## Considerations
We are looking for strong API methodologies. Consider edge cases and writing tests, as needed.
It’s okay to cut corners and “hardcode” things, just be prepared to answer questions about this in a follow up discussion .

### BONUS
Dockerize your application.
---

### Estimated Time: 3 hours

## Finishing Up
When finished, send us a link to your repo with the completed challenge, or zip up the repo and send to Ray.

### Good Luck! Feel free to reach out with any questions.
