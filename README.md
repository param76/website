# A simple video membership website built with Django.

This project shows how to create a video membership website using Django and Stripe billing.

## Getting Started

Create a stripe account and put your stripe publishable key and secret key inside `settings.py` as well as your publishable key inside `checkout.js` in the static folder. 


## Latest update of the code

Stripe changed their API to no longer allow a source being passed into a subscription. The code has been updated to now correctly bill a customer.

